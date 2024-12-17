#   SECURINETS ISITCOM Friendly CTF - Crypto Writeups 🐱‍💻

Welcome to the write-ups for the Crypto Challenges from the SECURINETS ISITCOM Friendly CTF! https://www.facebook.com/share/p/1AtFziBXjD/

As the author of these tasks, I aimed to design engaging challenges that would test everyone's cryptography skills. In this blog, I’ll go through the solutions for the six challenges I created, which cover a variety of topics like hash cracking, XOR encryption, and risks in RSA. 


Each challenge is crafted to be enjoyable while helping you learn, giving players a chance to boost their knowledge of real-world cryptographic techniques and attack methods. Whether you’re here to go over the challenges again or pick up new problem-solving tips, I hope you find these write-ups friendly and informative. 

Let’s jump into the solutions and explore the thought process behind each task together!



## Task 1:

![crackstation 1](https://github.com/user-attachments/assets/aa8cb993-add4-4693-9a02-789c8121dbf5)


Solution: This task is straightforward, as the name indicates. Let's search for "crack station" on Google, where we found a website to crack the hash [crackstation](https://crackstation.net/)

![image](https://github.com/user-attachments/assets/514efa1e-cd6b-4b75-9e68-d0fd471920e7)

and here we have our flag!

## Task 2:

![crackstation2](https://github.com/user-attachments/assets/471e98e9-8f3e-4ee7-b54e-b4dfed43ade1)


Solution: Let's check [crackstation](https://crackstation.net/) too for this hash:

![image](https://github.com/user-attachments/assets/33f47ff0-df16-43b2-b84f-90b0ae1c903d)

and here we have our flag!

## Task 3:

![econding looop](https://github.com/user-attachments/assets/b5535b78-15ad-4375-8ec5-e083f589aa6e)


I uploaded this encrypted flag for the challenge, so take a look!

      MzAgMzAgMzEgMzEgMzAgMzEgMzEgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzEgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzEgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzEgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzEgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzEgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzEgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzEgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzEgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzEgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzEgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzEgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzEgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzEgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzEgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzEgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzE=


We can see that the flag is encrypted in base64, so let's visit the CyberChef website to decode it. https://gchq.github.io/CyberChef/

![image](https://github.com/user-attachments/assets/c69df917-6268-4c37-bbf0-3ba5c8785650)

We observe that the output is in hex format, so let's proceed to decode it.

![image](https://github.com/user-attachments/assets/229a749b-e0a6-4047-916d-c941045b0517)

The output is in binary now, so let’s figure out how to decode it.

![image](https://github.com/user-attachments/assets/893c7172-5350-413f-82b3-d5cd19b3cdae)

And now we’ve got a decimal output! Let’s take a moment to decode it together:

![image](https://github.com/user-attachments/assets/a8cee7a7-9b6b-4caf-aa50-11abd5e736ae)

Finally, we found our flag, but it was still encrypted. We noticed that the flag consists only of characters without numbers, so I suspect it's a ROT13 encryption. Let's try to decode it:

![image](https://github.com/user-attachments/assets/17391d6d-6c89-4152-8ddf-99a5bb6c5a4f)

Here is our flag:

    SECURINETSISITCOM{ROT13-DECIMAL-BINARY-HEX-BASE64}

## Task 4:

![myxor](https://github.com/user-attachments/assets/fbcc789d-380b-475b-96a1-1c2424d20b0d)


 I uploaded this encrypted flag for the challenge, so take a look!

     382c2d323b3a3a2d31382c2a223d2d2824083a21262e3a20243c3121203d3037312320263f3b2724222c2b3722243a2d24363a2f2c2c3a2d3d3f3a2d2a3a251a63

### HINT: Remember the flag format and how it might help you in this challenge!


We are also given part of the plaintext flag, SECURINETSISITCOM{...}. Using this information, we can deduce part of the encryption key and eventually retrieve the full flag.

Solution Steps:
    
Step 1: Understand the XOR Encryption and don't forget these properties

![image](https://github.com/user-attachments/assets/8c461766-4520-406a-8d0f-bab12c7dd974)

 This challenge uses XOR encryption, where: "Cipher(encFlag) = Flag XOR Key" If we know part of the plaintext (Flag), we can deduce part of the key: "Key = Cipher XOR Flag"

Step 2: Convert the Cipher Text & XOR to Find the Key

The ciphertext is provided in hexadecimal format. First, we decode it for easier manipulation https://gchq.github.io/CyberChef/ :

![image](https://github.com/user-attachments/assets/d2c886b6-0c8f-443d-a7ee-38ee9aa1864b)

This reveals the key:  #kingisthekey# 

So let's get our flag:

![image](https://github.com/user-attachments/assets/362aaba1-8629-42c9-9bd0-03ec15d19e1d)

    SECURINETSISITCOM{NICE_YOU_FIND_THE_TRICK___GO_TO_THE_NEXT_TASK}

## Task 5:

![xor elliot](https://github.com/user-attachments/assets/90845467-6b68-442f-8e25-3eae024c1113)

### HINT: This challenge requires performing a visual XOR between the RGB bytes of the two images and note that you need to resize the images to decode it

We’re going to create a Python script that will help us perform bitwise XOR operations on images. I typically recommend using the OpenCV library, as it’s a great tool for this kind of work!

````python
import cv2

# Read two images. The size of both images must be the same.
img1=cv2.imread('hello.png')
img2=cv2.imread('world.jpg')

# Resize the img 2 to have the same size as img 1
img2 = cv2.resize(img2, (img1.shape[1], img1.shape[0]))



#Compute the bitwise XOR on two images using cv2.biwise_xor(img1, img2).
xor_img = cv2.bitwise_xor(img1,img2, mask = None)

#save the image
cv2.imwrite('flag.jpg',xor_img)

````

Here’s our new XORed image! Let’s go ahead and open it up.

![flag](https://github.com/user-attachments/assets/5ba4af94-d8cf-41ea-9e9b-38cd159e7961)

    SECURINETSISITCOM{XOR_1T_1F_U_C8N}


## Task 6:

![RSA MY LOVE](https://github.com/user-attachments/assets/3de971a2-797b-4b88-8dfe-c591bbd27f6e)

The attached file has everything you need about the task:

````
N = 18814840635346619874425333469811897321549418263501570889282825750834515074675420955536024872473333925100162290869450343342196370005147241590450746764679485718567750837860298441879336049949463769103929953264633072242523089509554532420960226194229074889893991993272393955287647019173019565996826761031489963195126291001577851134834313095727805927258826762839259238704853071924049305921348548805171136582998855037946513227862183246591156434241274337978149248881248098712196426195343743140711782990404627731190157041047720437406870278036078843043167368486244024032010310184530070850162225094426996919028658409155918085541
e = 0x3

encFlag = 26572349774532122558413822660787565800876859961042748864197505662294319821137420537449406034432755970252620682951620140376826571119571396577525308224469379695704886151366719681917316926664475491403254419941927069176375066837735027264004604420524982390706651874487308796663467648818962491218331170345389279578813057125
````

It’s interesting to note that this encryption method relies on a small public exponent, 𝑒=3. However, it can be a bit risky because it might be vulnerable to certain attacks, especially if the plaintext message is on the smaller side compared to the modulus N.

So we need to create a python script to exploit the small public exponent vulnerability in RSA encryption. If the plaintext 𝑚 is small enough that 
𝑚^𝑒 < 𝑁, the ciphertext c is simply 𝑚^𝑒. The script calculates the e-th root of 𝑐 (here 𝑒 = 0x3 = 3) to recover the plaintext directly, converting it to readable bytes.

````python
from sympy import root
from Crypto.Util.number import long_to_bytes

# Encrypted flag (ciphertext), modulus (N), and public exponent (e)
encFlag = 26572349774532122558413822660787565800876859961042748864197505662294319821137420537449406034432755970252620682951620140376826571119571396577525308224469379695704886151366719681917316926664475491403254419941927069176375066837735027264004604420524982390706651874487308796663467648818962491218331170345389279578813057125
N = 18814840635346619874425333469811897321549418263501570889282825750834515074675420955536024872473333925100162290869450343342196370005147241590450746764679485718567750837860298441879336049949463769103929953264633072242523089509554532420960226194229074889893991993272393955287647019173019565996826761031489963195126291001577851134834313095727805927258826762839259238704853071924049305921348548805171136582998855037946513227862183246591156434241274337978149248881248098712196426195343743140711782990404627731190157041047720437406870278036078843043167368486244024032010310184530070850162225094426996919028658409155918085541
e = 0x3

# Calculate the cube root of the ciphertext to recover the plaintext (m)
m = int(root(encFlag, e))

# Convert the plaintext (integer) to bytes
plaintext = long_to_bytes(m)

# Print the result
print(plaintext)

````

     Flag: SECURINETSISITCOM{Small_e_Is_Bad_My_Friend!} 
