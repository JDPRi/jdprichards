# Cryptool

<p style="font-size:17px; color:lightblue">
Welcome to my cryptool explainer, cryptool is a useful bit of software that can be used to demonstrate some of the ways you can encrypt and decrypt data, you can also analyse some encrypted text and analysis it to find the key to decrypt it.
</p>

<p style ="font-size:18px;color:blue">
Introduction to cryptool
</p>

<p style = "font-size:16px">
If you don't already have cryptool installed you can find it <a href="https://www.cryptool.org/en/ct1/downloads">here</a><br>
I will be using cryptool 1
<br><br>
When you first open cryptool you will see some plain text with some information on how to start. Then at the top there'll be many options for you to use inside cryptool, I'll try to walkthough some of the more basic ones.<br>
But your first view will look like this:<br><br>

<script>
img.resize {
  max-width:30%;
  max-height:20%;
}
</script>

<img src= "CryptoolImages\FirstView.png" class="resize">
</p>

<p style ="font-size:18px;color:blue">
Caeser Cipher:
</p>

<p style="font-size:16px">
The Caeser Cipher is a very basic encryption, it essentially increases the value of a character by a given about, example:<br>
Increasing A by a factor of 3, you would get D.<br> Then to go back you'll have to take 3 off D to get A.<br><br>
If you encrypted a string by a numerical caeser cipher, you'd increase each letter by the same amount.<br>
For example encrpting "hello world" by 4:
lipps asvph <br><br>
You can do this yourself by  creating a new file in <b style="color:red">File->New</b><br>
Then type some text in to encrypt<br>
Then to encrypt that you need to go <b style="color:red">Encrypt/Decrypt -> Symetric caeser / rot 13</b><br>
<br>
<img src= "CryptoolImages\CaesarCipher.png" class="resize">
<br>
You'll then be given a few options, keep all of the settings the same for now but the Key entry, this will give you an option to an alphabetic character of a number value, you can use the number character for now. You can then enter the value you want to increase the values.<br> This will show you the shift and what each character will turn into. To complete your encryption just click encrypt and you'll be shown your encrypted text. To decrypt you just do the same but press decrypt.<br><br>
You can mess around with this and find some of the things you can do with it, using different keys, using letters instead, looking at the text options and adding numbers and symbols to the ciphers alphabet.
</p>

<p style ="font-size:18px;color:blue">
Analysing Caeser Cipher:
</p>