# autotag
My personal auto toolbox. 
Used as reference for [Zero-TOTP](https://github.com/SeaweedbrainCY/zero-totp) and all [Seaweedbrain's projects](https://github.com/SeaweedbrainCY)

### How to install : 
```sh
curl https://raw.githubusercontent.com/SeaweedbrainCY/autotag/refs/heads/main/autotag > autotag
chmod u+x autotag
```
And then move autotag anywhere in your $PATH. 

### How to use : 
**Bump major/minor/fix versions :**
```sh
autotag -major
autotag -minor
autotag -fix
```

**Specify message tag**
```sh
autotag -major -m "message"
```

**Bump dev version**
```sh
autotag -dev
```
*This can be used alongside major/minor/fix flag*

**Set up custom version**
```sh
autotag -c v1.2.3
```
