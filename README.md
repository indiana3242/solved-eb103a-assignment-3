Download Link: https://assignmentchef.com/product/solved-eb103a-assignment-3
<br>
<ul>

 <li>Description</li>

 <li>The are 2 assignments. (1) To create an ER diagram with annotations; (2) To download, install, and open SQL 53 Power Architect.</li>

 <li>Precise submission details are given in Section 3.</li>

 <li>2 Assignments</li>

 <li>Below is the description of the application under consideration.</li>

 <li>For the third-person singular pronoun I will generally use “it” and its declensions.</li>

 <li>Some words are in bold. This has no semantic implications and they are written in this way to make the 59 reading easier.</li>

 <li>Do <em>not </em>make any assumptions about the application beyond the specifications listed.</li>

 <li>Following the notation we used in class, using draw.io and the shapes provided by it, produce an ER diagram 62 for the application. Do not use any other notation. For example, you may not use cardinality constraints in</li>

 <li>your diagram.</li>

 <li>Because the software you will use has slight differences compared to what we did, please consult the file 65 pdf so that you know how to produce your diagram. 66 Do not optimize your design, just follow the specification given.</li>

</ul>

67 Anything that cannot be specified in the ER diagram, put as annotations in text03.txt file, as described in 68 Item 1 of Section 3, starting with 1. and continuing as needed.

69                  Do <em>not </em>put anything in the annotations that can be reflected in the ER diagram, make sure that the diagram 70                      reflects that. The idea is for you to think what’s needed and where to put it: the diagram or the annotations.

71                  Note that you cannot make any assumptions that are not forced by the specifications. For example, if the 72                      value of an attribute is not required to be known, you cannot assume that it is always known.

73                  There are Companies. Companies have an attribute TIN (Tax Identification Number) and it is always 74              known. No two Companies can have the same TIN.

75 A Company Helps exactly one Company; a Company may Help itself. For such a Help, a Company 76 charges a Fee and its value is not necessarily known.

77 A Company may Own Stores and no two Companies may Own the same Store. Each Store has at78 tributes Number and Size. Number is always known and no two Stores Owned by the same Company 79 may have the same Number. If Size is known, it is at least 100,000.

80                  There are Books. A Book has two attributes ISBN and Price. ISBN is always known and no two books 81             can have the same ISBN.

82 Stores Sell Books. If a Store Sells a Book, we may know the StartDate when that Store started 83 selling that Book.

<ul>

 <li>Sales may be Approved by one or more Companies.</li>

 <li>The domains of the attributes have not been specified.</li>

 <li>Start with the given ER03.drawio but put your own NetID in the cloud drawn there.</li>

 <li>If the system does not allow you to upload ER03.drawio, rename your ER03.drawio to be ER03.txt. Then 88 upload ER03.txt, and state that you have done that in Item 1b of Section 3.</li>

 <li>You will need to use SQL Power Architect to specify relational databases in a future assignment. Please</li>

 <li>download and install the latest version of the community edition from <a href="http://www.bestofbi.com/page/architect_download_os">http://www.bestofbi.com/page/ </a>91 <a href="http://www.bestofbi.com/page/architect_download_os">architect_download_os</a><a href="http://www.bestofbi.com/page/architect_download_os">.</a> Make sure that you can open it.</li>

 <li>You may encounter some difficulties running the software so here are possible workarounds.</li>

 <li>(a) A number of students in a previous class could not make the Mac version work on Mac, but the 94 Unix/Generic version did work. Please use the link for direct download : <a href="http://www.bestofbi.com/downloads/architect/1.0.9/SQL-Power-Architect-generic-1.0.9.tar.gz">http://www.bestofbi.com/</a></li>

 <li><a href="http://www.bestofbi.com/downloads/architect/1.0.9/SQL-Power-Architect-generic-1.0.9.tar.gz">downloads/architect/1.0.9/SQL-Power-Architect-generic-1.0.9.tar.gz</a><a href="http://www.bestofbi.com/downloads/architect/1.0.9/SQL-Power-Architect-generic-1.0.9.tar.gz">.</a></li>

 <li>Detailed steps can be found here : <a href="http://www.bestofbi.com/page/architect-start">http://www.bestofbi.com/page/architect-star</a><a href="http://www.bestofbi.com/page/architect-start"><sub>t</sub></a></li>

 <li>Also, if your Java version is too old you may need to update it. Please see <a href="https://www.java.com/en/download/manual.jsp">https://www.java.com</a><a href="https://www.java.com/en/download/manual.jsp"><sub>/</sub></a></li>

 <li><a href="https://www.java.com/en/download/manual.jsp">en/download/manual.jsp</a><a href="https://www.java.com/en/download/manual.jsp">.</a></li>

 <li>(b) Sometimes it is not possible to save a new file. This bug is intermittent. However, it was always possible to</li>

 <li>open an existing file, modify it, and just save it. Therefore a blank file relationalDatabase.architect 101 is enclosed. You can just copy it to a directory of your choice and work with it.</li>

 <li>State in text03.txt whether you have installed SQL Power Architect and were able to open it.</li>

 <li>Modify text03.txt by putting in it</li>

 <li>Your metadata</li>

 <li>The list of the annotations as requested above</li>

 <li>Have you done what is requested in Item 2 of Section 2.2? If that’s the case, just write “Yes”.</li>

 <li>If you have not done so, explain why. And if you run into difficulties doing that part of the assignment 108 after applying all the workarounds described, also send email to Nancy Nigam, mailto:<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="3b5555090a0d087b55424e155e5f4e">[email protected]</a>, 109             explaining what the difficulties were.</li>

</ul>