Contributing to ntru-crypto
============================
This page describes how to contribute to the NTRU GitHub source control repository and the various ways to interact with the code and other assets.  Contributions to the project will come in various forms including changes/improvements to the reference code, attacks against the algorithm, attacks against the reference code, implementation documentation, test vectors and other such things.    
Key branches
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
1.	Try to submit pull requests against the latest *-wip branch for easier merging

2.	Try not to pollute your pull request with unintended changes--keep them simple and small

Coding Standards
================
C/C++
-----

Java
----

Attestation
===========
If you make substantive changes to a file or create new assets, you may wish to add a copyright line for yourself or for the company on whose behalf you work. Below are sample copyright lines for an individual contributor and a company:
Copyright (C) 2011 John Smith (jsmith@example.com)
Copyright (C) 2011 Company Inc. All rights reserved.
In addition, make sure that any new source code or assets you introduce reference the project dual license text at the beginning of the file. If you are the author of a new file, preferred license text is:
    /*******************************************************************************
     * <<Module Name>>
     * NTRU Cryptography Reference Source Code
     * Copyright (c) <<year>>, by <<Author/Company>>
     * 
     * All rights reserved. 
     *
     * Dual License
     * This program and the accompanying materials are made available under the terms of   
     * the GPL version 3 license for non-commercial use and the Security Innovation 
     * Commercial License for commercial applications. Both of which accompany this 
     * distribution and are also available at http://www.gnu.org/licenses/gpl-3.0.html   
     * and http://www.securityinnovation.com/NTRUlicense.doc   
     *
     *****************************************************************************/

Respond to reviewers
====================
Make sure to respond to all comments and questions from folks who review your code and provide the same courtesy to folks whose code you review 

License
=======
By contributing your code, you agree to license your contribution under the dual license terms of the GPL version 3 and the Security Innovation Commercial License
http://www.gnu.org/licenses/gpl-3.0.html   
http://www.securityinnovation.com/NTRUlicense.doc   
