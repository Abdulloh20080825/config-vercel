# How to use this config

1 Time open a cmd end create a vercel.json file and copy and paste this config to your project

<pre>
{ 
        "version": 2,
        "builds": [{"src": "./index.js", "use": "@vercel/node"}],
        "routes": [{"src": "/(.*)", "dest": "/"}]
}
</pre>
