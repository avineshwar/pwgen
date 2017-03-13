# pwgen
Taken from netmeister.org, it helps to generate a reasonably random password. A cmdline trick for MAC users is also present.




Steps to follow:
  1. Create the pwgen in ~/bin/ and chmod pwgen to 755
  2. We are ready to spit out random passwords
  
  
As a bonus trick, after the above steps have been followed, MacOSX users can do this from their terminal:
`security add-generic-password -a ${USER} -s SomeNameHere -w ~/bin/pwgen`

This will add into the keychain, "SomeNameHere" as an application with a password which was given by pwgen.





Credits:
        Professor Jan Schaumann,
        Stevens Institute of Technology
