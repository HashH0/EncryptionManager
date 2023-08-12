# EncryptionManager

## About
EncryptionManager is a simple project for encrypting data using matrixtranslocation. It is important to note that this type of encryption is not the most secure method of encryption. However, it offers a certain level of encryption

## Usage
### Encryption
At first copy the .kt file in the github repo above. Then simply create a new String which is equal to the encryption() function. Add the String you want to encrypt as parameter.
````kotlin
var encrypted: String = EncryptionManager.encryption("ADD STRING HERE")
````

### Decryption
At first copy the .kt file in the github repo above. Then simply create a new String which is equal to the decryption() function. Add the encrypted String as parameter of the method.
````kotlin
var decrypted: String = EncryptionManager.decryption("ADD ENCRYPTED STRING HERE")
````

## Dependencies
There is no dependency needed for the methods to work. Kotlin and the associated Java Runtime are the only requirements.
