# CTF Module 1
solution: websitesarestupendous

stage 1: The website says i should "inspect" the website. maybe i should inspect element?
![image info](./screenshots/1.png)

bingo! we found the first part of the key

stage 2: the hint says that we should check the "style" of the page. maybe we should add style sheets?
![image info](./screenshots/2.png)

shazam! we found the second part of the key

stage 3: the hint talks about something about scripts. maybe hes talking about javascript? lets read the javascript console real quick
![image info](./screenshots/3.png)

abracadabra! we found the third part of the key

stage 4: the javascript file itself talks about a README. maybe we should look for a common file in github pages, README.md?
![image info](./screenshots/4.png)

alakazam! we found the fourth part of the key

# CTF Module 2
Solution: steganographyisreallycool

Stage 1: the first hint says we should analyze the titlebar, and the webite inspect element lets us download something called titlebar.png
![image info](./screenshots/19.png)

maybe we should put it through a steganography analyzer?
![image info](./screenshots/20.png)

ta-da! we found the first part of the key

Stage 2: the hint says we should find the back most part of a website, maybe hes talking about the background?
![image info](./screenshots/21.png)

ok, lets put it into the stego inspector

![image info](./screenshots/22.png)

shazam! we found the second part of the key

Stage 3: the hint talks about foot and feet, maybe hes talking about the footer?
![image info](./screenshots/23.png)

ok, lets download the footer and analyze it

![image info](./screenshots/24.png)

open sesame! we found the third part of the key

Stage 4: if i highlight the page, there seems to be some part 4 code hidden in the webpage
![image info](./screenshots/26.png)

horse and hattock! we found the fourth part of the key

# CTF Module 3
Solution: thisisacipher

Stage 1: the first part looks like a bunch of numbers, what is the most common use of text, however?
![image info](./screenshots/5.png)

It seems to be ASCII, maybe the code were using is ASCII?
![image info](./screenshots/6.png)

hocus-pocus! we found the first part of the key

Stage 2: the next part looks like base64, maybe the code is base64?
![image info](./screenshots/8.png)

presto-chango! we found the second part of the key

Stage 3: the hint talks about binary, maybe this part of the cypher is ASCII in binary?
![image info](./screenshots/10.png)
![image info](./screenshots/11.png)

presto! we found the third part of the key

Stage 4: the hint talks about the most common cipher, maybe we should look that up?
![image info](./screenshots/12.png)

ok so the most common cipher is rot13, maybe the cipher is rot13?

![image info](./screenshots/13.png)

voila! we found the fourth part of the key

# CTF Module 4

Solution: i54c2f14206b28a253d31c453e2716971digitalforensics

Stage 1: the first part gives us a link to a zip and and we open it to find some files 
![image info](./screenshots/14.png)

one of the files contains the first code! wow!

![image info](./screenshots/15.png)

Stage 2: the next hint talks about something about md5 hash? maybe I should open the file called md5 hash
![image info](./screenshots/16.png)

ok, so the hash of the file is the second part of the code? ahhah1!

Stage 3: the hint talks about how the hash is a password, and one of the files is a password prottected zip file. hm.
![image info](./screenshots/17.png)
![image info](./screenshots/28.png)

ok! we found the third part of the key

Stage 4: the last hint asks us what the parent folder is called, is it forensics?
![image info](./screenshots/18.png)

yup!