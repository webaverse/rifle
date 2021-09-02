# rifle

Rifle that can shoot projectiles. You can hold down right click in Webaverse to aim more accurately.

![](https://i.imgur.com/83W4yfc.png)

Guide: https://docs.webaverse.com/docs/create/guns


## `.metaversefile`

The .metaversefile goes in the directory with the GLB file in order to create the XRpackage.


```
{
  "name": "rifle",
  "description": "Rifle XRPackage",
  "start_url": "rifle.glb",
  "components": [
    {
      "type": "use",
      "subtype": "gun",
      "useAnimation": "rifle"
    }
  ]
}
```
