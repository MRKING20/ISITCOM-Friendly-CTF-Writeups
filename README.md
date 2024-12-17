#   SECURINETS ISITCOM Friendly CTF - Writeups 🐱‍💻

Welcome to the write-ups for the Crypto Challenges from the SECURINETS ISITCOM Friendly CTF! https://www.facebook.com/share/p/1AtFziBXjD/

As the author of these tasks, I aimed to design engaging challenges that would test everyone's cryptography skills. In this blog, I’ll go through the solutions for the six challenges I created, which cover a variety of topics like hash cracking, XOR encryption, and risks in RSA. 


Each challenge is crafted to be enjoyable while helping you learn, giving players a chance to boost their knowledge of real-world cryptographic techniques and attack methods. Whether you’re here to go over the challenges again or pick up new problem-solving tips, I hope you find these write-ups friendly and informative. 

Let’s jump into the solutions and explore the thought process behind each task together!



## Task 1:

  ![crackstation 1](https://github.com/user-attachments/assets/bb73661a-45f2-4045-8e0a-3654fa71e871)


Solution: This task is straightforward, as the name indicates. Let's search for "crack station" on Google, where we found a website to crack the hash [crackstation](https://crackstation.net/)

![image](https://github.com/user-attachments/assets/0df9cd00-769d-4299-a533-8a270bd69bb4)

and here we have our flag!

## Task 2:

  ![crackstation2](https://github.com/user-attachments/assets/a84eedfd-3ef1-4789-a7ce-435657625e12)


Solution: Let's check [crackstation](https://crackstation.net/) too for this hash:

![image](https://github.com/user-attachments/assets/905febcf-c65f-4309-932a-149f5cccde4c)

and here we have our flag!

## Task 3:

  ![econding looop](https://github.com/user-attachments/assets/c757e612-be39-454e-9544-a7ac14e79d09)


I uploaded this encrypted flag for the challenge, so take a look!

      MzAgMzAgMzEgMzEgMzAgMzEgMzEgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzEgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzEgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzEgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzEgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzEgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzEgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzEgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzEgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzEgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzEgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzEgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzEgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzEgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzEgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzEgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzEgMzAgMjAgMzAgMzAgMzEgMzAgMzAgMzAgMzAgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzAgMzEgMjAgMzAgMzAgMzEgMzEgMzAgMzAgMzEgMzAgMjAgMzAgMzAgMzEgMzEgMzAgMzEgMzAgMzE=


We can see that the flag is encrypted in base64, so let's visit the CyberChef website to decode it. https://gchq.github.io/CyberChef/

![image](https://github.com/user-attachments/assets/530467f1-6806-4cc1-8a6b-6d730c96857b)

We observe that the output is in hex format, so let's proceed to decode it.

![image](https://github.com/user-attachments/assets/10b9c424-9a58-4d06-b075-dfee252e9699)

The output is in binary now, so let’s figure out how to decode it.

![image](https://github.com/user-attachments/assets/dcdaa532-96d1-4697-8a8b-1e2d2c7170e1)

And now we’ve got a decimal output! Let’s take a moment to decode it together:

![image](https://github.com/user-attachments/assets/0a706a8f-16df-4325-b97e-89a83c8d2519)

Finally, we found our flag, but it was still encrypted. We noticed that the flag consists only of characters without numbers, so I suspect it's a ROT13 encryption. Let's try to decode it:

![image](https://github.com/user-attachments/assets/8c656d52-5d09-4af5-9035-789634c64a94) 

Here is our flag:

    SECURINETSISITCOM{ROT13-DECIMAL-BINARY-HEX-BASE64}

## Task 4:

![myxor](https://github.com/user-attachments/assets/e5040228-234d-4c72-812a-7550d1136d9d)


 I uploaded this encrypted flag for the challenge, so take a look!

     382c2d323b3a3a2d31382c2a223d2d2824083a21262e3a20243c3121203d3037312320263f3b2724222c2b3722243a2d24363a2f2c2c3a2d3d3f3a2d2a3a251a63

### HINT: Remember the flag format and how it might help you in this challenge!


We are also given part of the plaintext flag, SECURINETSISITCOM{...}. Using this information, we can deduce part of the encryption key and eventually retrieve the full flag.

Solution Steps:
    
Step 1: Understand the XOR Encryption and don't forget these properties

 ![image](https://github.com/user-attachments/assets/548d5cd5-fb07-4e38-b763-844b448e3a9b)

 This challenge uses XOR encryption, where: "Cipher(encFlag) = Flag XOR Key" If we know part of the plaintext (Flag), we can deduce part of the key: "Key = Cipher XOR Flag"

Step 2: Convert the Cipher Text & XOR to Find the Key

The ciphertext is provided in hexadecimal format. First, we decode it for easier manipulation https://gchq.github.io/CyberChef/ :

![image](https://github.com/user-attachments/assets/8ccd6345-9329-49f7-85b7-88c76b520677)

This reveals the key:  #kingisthekey# 

So let's get our flag:

![image](https://github.com/user-attachments/assets/828f38c5-c78b-41a0-8e72-d1a5f4ac54cd)

    SECURINETSISITCOM{NICE_YOU_FIND_THE_TRICK___GO_TO_THE_NEXT_TASK}

## Task 5:

![xor elliot](https://github.com/user-attachments/assets/b8b51b02-8199-421b-a540-eb549ffb12ba)

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

![flag](https://github.com/user-attachments/assets/2ec3a70c-035d-45de-80a8-0ec3da1632f1)

    SECURINETSISITCOM{XOR_1T_1F_U_C8N}


## Task 6:

![RSA MY LOVE](https://github.com/user-attachments/assets/1743cffd-87c5-46d9-8a24-b15e796ff802)

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
