<script>
  import "carbon-components-svelte/css/g10.css";
  import {Button, ContentSwitcher, Switch, PasswordInput, TextInput, TextArea, CodeSnippet} from "carbon-components-svelte";
  import Copy from "carbon-icons-svelte/lib/Copy.svelte";
</script>



<h1>Key Encryptor</h1>

<ContentSwitcher>
  <Switch text="Encrypt" />
  <Switch text="Decrypt" />
</ContentSwitcher>


<PasswordInput 
  labelText="Secret Key"
  helperText="Secret key is used to encrypt and decrypt string"
  placeholder="Enter your secret key"
/>

<div>
  
</div>

<PasswordInput 
  labelText="Password"
  helperText="The password is to be encrypted and decrypted"
  placeholder="Enter your password to be encrypted or decrypted"
/>

<Button>
  Encrypt
</Button>

<CodeSnippet 
  code = "print encrypted string"
/>