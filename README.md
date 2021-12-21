# ASCredentialProviderViewController_Sample

A simple project to summon the password autofill screen in iOS and then inject a password (hard coded into the passwordSelected function in CredentialProviderViewController. 

`let passwordCredential = ASPasswordCredential(user: "j_appleseed", password: "apple1234")`

Added screens as these need to be manually enabled in Keyboard settings. Once selected, injects into the fields.

This is based on the Credential Provider entitlement documented at https://developer.apple.com/documentation/authenticationservices/ascredentialproviderviewcontroller
