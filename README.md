# hash_encrypter
(Project at work. In a close future, the description will be better elaborate here.) </br></br>
<h3>Exemple of features:</h3>
 <video width="320" height="240" controls>
  <source src="hashEncrypterSmallVersion7.mp4" type="video/mp4">
Your browser does not support the video tag.
</video> 
 <video width="320" height="240" src="hashEncrypterSmallVersion7.mp4"></video> 


<a href='https://bernp.github.io/hash-encrypter/' target="_blank">Click here to access the website!<a></br></br>

<h3>Proposal:</h3>
Make a method that can create an Encrypter by a generalist approach - develop a method that can be replied to create an infinite number of encryption functions, or, in better words, make possible for everyone creates a better Encrypter by just coping this code and change the logic, fake part generation or shuffle function. Thus, by using this generic approach, develop an Encrypter that can hide the encrypted code in phrases or in images. Therefore, the Encrypter will be developed, at first, as a website and, after all the tests are conducted, be converted into a smartphone app.</br>

<h3>Final objective:</h3>
Make an app that can be easily used to hide messages and photos in a way that masks that was encrypted - an ordinary person that sees the encrypted message or photo can’t even notice that it has some code hidden there.</br>

<h3>Project current stage:</h3>
At the moment, the project can receive an input, encrypt it and compressed it (it can be easily visualized with the encryption diagram image below). The input just can be a text - what in future will be any file type - and the output is a compacted version of an integer sequence.
The mask function - that transform the compressed code into an image or text, what impossibility an outsider individual to link the output to a possible hided message - is in the start of the development fase. At the moment, the encrypter code can be masked into a "grocery store list" or just stay as a code. The way of the "Mask to grocery store list" was implemented has two major problems, first is the dependency on a non-mutable database, what makes the decrypt don't work with an updated database; the second issue is a huge increment of the output length that happens. </br></br>

<img id="diagram" rel="preload" src="images/complete_diagram.png">

<h3>Example of the functionalities:</h3>
<img id="diagram" rel="preload" src="images/example.png">
