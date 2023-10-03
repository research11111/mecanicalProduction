This illustrate lake of mecanical production certification from github platform.  

1. production from the workflow file - certified by platform  
  user has garantee that the artifact is the product of the source code (and actions additionnal modifications but modifications could be retraced)  
  this lead to github has a certified autority for software, not responsible of what the developper has encoded but garant of the fact that what developper has published on github  
  is in the binary, nothing more nothing less.  

2. non certified production  
  developper may update manually later artifacts coming from the release process, so for end user "consumers" there is no garantee that binaries are product of the source code  


Proof:  
  on tag [v0](https://github.com/research11111/mecanicalProduction/tree/v0) a.txt contains "a", but the [release associated to v0 tag](https://github.com/research11111/mecanicalProduction/releases/tag/v0) contains a file a.txt with "ok" content

Github should provide a way to user to known if artifacts from releases came from a developper action or just from the workflow file  
Not blocking manual edition from developper side but provide end user that information (like "verified" tags)   


