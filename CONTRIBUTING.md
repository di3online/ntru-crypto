Contributing to ntru-crypto
============================
This page describes how to contribute to the NTRU GitHub source control repository and the various ways to interact with the code and other assets.  Contributions to the project will come in various forms including changes/improvements to the reference code, attacks against the algorithm, attacks against the reference code, implementation documentation, test vectors and other such things.   

Contributor Agreement
=====================
To contribute code you must read, sign and return the CONTRIBUTOR AGREEMENT included in this distribution.  Signed copies may either be converted to PDF and mailed to ntru-crypto@securityinnovation.com or faxed to +1.978.694.1666.  

Content
=======
**Key branches**

1.	master is the latest, deployed version.

2.	gh-pages is the hosted docs (not to be used for pull requests).

3.	*-wip is the official work in progress branch for the next release.

Reporting issues
================
We only accept issues that are bug reports or feature requests. Bugs must be isolated and reproducible problems that we can fix within the ntru-crypto core. Please read the following guidelines before opening any issue.

1.	Search for existing issues. We get a lot of duplicate issues, and you'd help us out a lot by first checking if someone else has reported the same issue. Moreover, the issue may have already been resolved with a fix available.

2.	Create an isolated and reproducible test case. Provide a sample that reproduces the bug in 25 lines or less.

Share as much information as possible. Include operating system and version, browser and version, version of ntru-crypto, customized or vanilla build, etc. where appropriate. Also include steps to reproduce the bug.

Pull requests
=============
1.	Try to submit pull requests against the latest *-wip branch for easier merging

2.	Try not to pollute your pull request with unintended changes--keep them simple and small

Coding Standards
================
C/C++
-----

Java
----

Respond to reviewers
====================
Make sure to respond to all comments and questions from folks who review your code and provide the same courtesy to folks whose code you review 

Copyright and Attestation
===========
Security Innovation, Inc. retains ownership and copyright to all code in the project including that which is contributed by Security Innovation and all third parties. If you make substantive changes to a file or create new assets, you may wish to add a copyright line for yourself or for the company on whose behalf you work in addition to the standard required copyright heading below. Some sample copyright lines for an individual contributor and a company:

 * Copyright (C) 2011 John Smith (jsmith@example.com)
 * Copyright (C) 2011 Company Inc. All rights reserved.

Make sure that any new source code or assets you introduce reference the project dual license text at the beginning of the file. If you are the author of a new file, preferred license text is:

    /*******************************************************************************
     * <<Module Name>>
     * NTRU Cryptography Reference Source Code
     * Copyright (c) 2009-2013, by Security Innovation, Inc. All rights reserved. 
     *
     * Redistribution and use in source and binary forms, with or without
	 * modification, are permitted provided that the following conditions
	 * are met:
	 *
	 * 1.  Redistributions of source code must retain the above copyright
	 *     notice, this list of conditions and the following disclaimer.
	 * 2.  Redistributions in binary form must reproduce the above copyright
	 *     notice, this list of conditions and the following disclaimer in the
	 *     documentation and/or other materials provided with the distribution.
	 *	
	 * THIS SOFTWARE IS PROVIDED BY SECURITY INNOVATION INC. AND ITS CONTRIBUTORS 
	 * ``AS IS'' AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO,THE 
	 * IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
	 * DISCLAIMED. IN NO EVENT SHALL SECURITY INNOVATION INC. OR ITS CONTRIBUTORS BE 
	 * LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL 
	 * DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR 
	 * SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED 
	 * AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
	 * (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
	 * SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
	 *
	 *
	 * This program and the accompanying materials are made available under the terms of   
	 * the GPL version 3 license for non-commercial use and the Security Innovation 
	 * Commercial License for commercial applications; both of which accompany this 
	 * distribution and are also available at:
	 *
	 *		 http://www.gnu.org/licenses/gpl-3.0.html   
	 * 						and 
	 *		 http://www.securityinnovation.com/NTRUlicense.doc 
	 *
	 *******************************************************************************/
	 

License
=======
By contributing your code, you agree to comply with terms of the copyright and to license your contribution under the dual license terms of the GPL version 3 and the Security Innovation Commercial License; and provide the contributions free of licensing fees or other restrictions that might interfere with the execution of either license.

http://www.gnu.org/licenses/gpl-3.0.html   
http://www.securityinnovation.com/NTRUlicense.doc 

  
	

  


