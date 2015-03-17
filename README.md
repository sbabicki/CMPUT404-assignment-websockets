CMPUT404-assignment-websockets
==============================

CMPUT404-assignment-websockets

See requirements.org (plain-text) for a description of the project.

Make a shared state Websockets drawing program

Prereqs
=======

pip install flask-sockets

pip install ws4py

pip install gunicorn

Contributors / Licensing
========================

Generally everything is LICENSE'D under the Apache 2 license by Abram Hindle.

freetests.py is LICENSE'D under a BSD-like license:

From ws4py

Copyright (c) 2011-2014, Sylvain Hellegouarch, Abram Hindle
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

 * Redistributions of source code must retain the above copyright notice,
   this list of conditions and the following disclaimer.
 * Redistributions in binary form must reproduce the above copyright
   notice, this list of conditions and the following disclaimer in the
   documentation and/or other materials provided with the distribution.
 * Neither the name of ws4py nor the names of its contributors may be used
   to endorse or promote products derived from this software without
   specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
POSSIBILITY OF SUCH DAMAGE.


#Modifications Description:
###server.py
- Modified to meet requirements 

###index.html
- Modified to meet requirements <br>
- Visual changes: 
colour actively changes as user continues to draw on canvas, 
size of up/down click circle decreased

###virt_env/
- Created a virtual environment to use in order to have the correct prereqs


#Resources Used: 
Used code by Abram Hindle:
<br>
<br>http://webdocs.cs.ualberta.ca/~hindle1/2014/CMPUT404-Javascript-Slides/#/8 
<br>Accessed on Feb. 28 2015
<br>
<br>https://github.com/abramhindle/WebSocketsExamples/blob/master/static/broadcast.html
<br>Accessed on Mar. 16 2015
<br>
<br>https://github.com/abramhindle/WebSocketsExamples/blob/master/broadcaster.py 
<br>Accessed on Mar. 16 2015
<br>
<br>Note: All functions taken from these sources are sited within the code. 


#Collaborators:
None
