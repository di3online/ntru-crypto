Coming Soon!!
============

ntru-crypto
===========

Open Source NTRU Public Key Cryptography Algorithm and Reference Code

Key Contacts:

* Dr. William Whyte
* Dr. Mark Etzel
* Mr. Peter Jenney


Contacts may be reached by sending mail to ntru-crypto@securityinnovation.com

Project Overview
================
Security Innovation, the owner of the NTRU public key cryptography system, made the intellectual property and a sample implementation available under the Gnu Public License (GPL) in 2013 with the goal of enabling more widespread adoption of this superior cryptographic technology. The system is also available for commercial use under the terms of the Security Innovation Commercial License.

NTRU represents a significant improvement in the Public Key cryptography world—it’s faster, stronger and smaller than virtually any other system in use and it’s quantum computer resistant, making it the best choice for current projects with lifetimes that extend into the post quantum computer age.  

Here are a few facts about the system:

What is NTRU?
-------------
NTRU is an asymmetric (public/private key) cryptosystem.  It is a leading alternative to RSA and ECC as it is faster and quantum resistant.  There are two NTRU based algorithms:  NTRU Encrypt and NTRU Sign.  Both cryptosystems are being released under GPL. The portable C/C++ & Java implementation in this project is also available under GPL.

What makes NTRU fast?
---------------------
Because it is based on different math from RSA and ECC, the NTRU algorithm has different cryptographic properties.   At comparable cryptographic strength, NTRU performs costly private key operations much faster than RSA or ECC.  In addition, NTRU's comparative performance increases with the level of security required.  As key sizes increase by a factor of n, RSA's operations/second decrease by about n3 whereas NTRU's decrease at n2.

What makes NTRU quantum computing resistant?
--------------------------------------------
NTRU is currently not known to be vulnerable to algorithms based on quantum computers, unlike RSA or its other challenger, Elliptic Curve Cryptography. A working, full-scale quantum computer running the process known as “Shor’s algorithm” would be able to break RSA or ECC of any practical size in negligible time. In contrast, NTRU’s security is reduced only slightly by quantum computers. This has been validated by external reviewers such as the National Institute of Standards and Technology (NIST), who in a 2009 survey referenced NTRU as justification for the statement that “there are viable alternatives for both public key encryption and signatures that are not vulnerable to Shor’s Algorithm”.

What is NTRU's history and peer review?
---------------------------------------
NTRU was invented in 1996 based on a completely different mathematical problems from RSA and Elliptic Curve called the “Approximate close lattice vector problem.”  It has been published, reviewed in scholarly journals, and presented at Crypto, Eurocrypt, RSA. The NTRU approach to lattice-based cryptography, which uses a particular type of lattice known as an “ideal lattice”, has been a catalyst for the development of other efficient lattice-based cryptographic primitives, most notably Gentry’s approach to fully homomorphic encryption.

How fast is NTRU?
-----------------
At comparable cryptographic strength, NTRU performs the costly private key operations much faster than RSA. 

    Security  NTRU Key Size     ECC   RSA     NTRU Ops/Sec.   ECC   RSA
    Level     Std.    Opt.       Key Size     Std.    Opt.     Ops/Sec.
    112       5951	  4411	    224	  2048	  2284	  10638	  951	  156
    128	      6743	  4829	    256	  4096	  1896	  9901	  650	  12
    192	      9757	  6523	    384	  7680	  1034	  6849	  285	  8
    256	      12881	  8173	    512	  15360	  638     5000	  116	  1
    

Much of the performance impact in SSL comes from the use of public key cryptography, which is used to initiate new sessions (session “handshakes”).  During session handshakes, the main public key activity consuming server resources is decryption of the session key provided by each client.  Performance increases in decryption have a significant impact on server performance. At current levels of activity, for a server using NTRU, the server time spent peforming public key cryptography will become negligible. CyaSSL+NTRU, a product that uses the algoritm runs 20x to 200x faster than openSSL RSA.

Has NTRU's speed been verified by third parties?
------------------------------------------------
Yes.  The Department of Electrical Engineering at the University of Leuven released a report entitled Speed records for NTRU. in which they write: "NTRU is extremely fast on parallelizable processors."

Has NTRU been standardized?
---------------------------
Yes.  NTRU has been adopted in two standards.  By IEEE and the Financial industries X9 standards.
(i) IEEE P1363 Working Group for Standards In Public Key Cryptography. This working group, active since 1992, has standardized many different techniques in public key cryptography. The standard IEEE Std 1363.1, issued in 2008, standardizes lattice-based public key cryptography, especially NTRUEncrypt. Other projects include or have included RSA, discrete log, elliptic curve discrete log, strong password-based techniques, and cryptography based on pairings.  IEEE 1363 Working Group Home Page

Is NTRU Patented?
-----------------
Yes. The patents will still be enforced but may be used under the GPL, i.e. under the condition that any work that uses them is also made available under the GPL. The patents and the code implementations are also available under standard commercial terms.

Where can I get more technical information
------------------------------------------
Go to https://www.securityinnovation.com/security-lab/crypto.html which is where we’ve collected a boatload of content on NTRU including NIST reports, the math and other very useful stuff.
