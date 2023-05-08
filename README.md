Download Link: https://assignmentchef.com/product/solved-relational-model-assignment-cs5200-introduction-to-relational-databases
<br>
<span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">Consider the UML class diagram shown below. Create the corresponding SQL that implements the equivalent relational model, fulfills the use cases, implements the relations, and enforces the constraints. </span><u style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">​</u><a style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;" href="https://docs.google.com/document/d/1i7yCzoVwdVRBsNzg9lmY-hCyf6WoSvLzv8ChKnKsV7E/edit?usp=sharing">A link to this assignment can be found here</a><span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">​.</span>

<h1>UML Class Diagram</h1>




Creating a remote database on Heroku:

At this point you should have a working local and remote development enviornment. If not, make sure to follow the instructions for setting up a remote account, remote application, and a development environment as described in <u>​</u><a href="https://docs.google.com/presentation/d/1jkBylv9qA-ULEJmlx9Asb378dOdn2xj2tU5kDBksXJU/edit?usp=sharing">Settingup</a> <a href="https://docs.google.com/presentation/d/1jkBylv9qA-ULEJmlx9Asb378dOdn2xj2tU5kDBksXJU/edit?usp=sharing">a</a> <a href="https://docs.google.com/presentation/d/1jkBylv9qA-ULEJmlx9Asb378dOdn2xj2tU5kDBksXJU/edit?usp=sharing">Development</a> <a href="https://docs.google.com/presentation/d/1jkBylv9qA-ULEJmlx9Asb378dOdn2xj2tU5kDBksXJU/edit?usp=sharing">Environment</a> lecture. Once the environment is setup, create and deploy a Spring Boot application on Heroku as describe in <a href="https://docs.google.com/presentation/d/1Dt3CqNEFOBuJYa5MvslzINEYphKWjkR6fydm_b62X_0/edit?usp=sharing">Deploying</a> <a href="https://docs.google.com/presentation/d/1Dt3CqNEFOBuJYa5MvslzINEYphKWjkR6fydm_b62X_0/edit?usp=sharing">Spring</a> <a href="https://docs.google.com/presentation/d/1Dt3CqNEFOBuJYa5MvslzINEYphKWjkR6fydm_b62X_0/edit?usp=sharing">Boot</a> <a href="https://docs.google.com/presentation/d/1Dt3CqNEFOBuJYa5MvslzINEYphKWjkR6fydm_b62X_0/edit?usp=sharing">Web</a> <a href="https://docs.google.com/presentation/d/1Dt3CqNEFOBuJYa5MvslzINEYphKWjkR6fydm_b62X_0/edit?usp=sharing">Applications</a> <a href="https://docs.google.com/presentation/d/1Dt3CqNEFOBuJYa5MvslzINEYphKWjkR6fydm_b62X_0/edit?usp=sharing">to</a> <a href="https://docs.google.com/presentation/d/1Dt3CqNEFOBuJYa5MvslzINEYphKWjkR6fydm_b62X_0/edit?usp=sharing">Heroku</a><u>​</u><a href="https://docs.google.com/presentation/d/1Dt3CqNEFOBuJYa5MvslzINEYphKWjkR6fydm_b62X_0/edit?usp=sharing">.</a> Finally, add a remote MySQL database to the remote development environment as described in ​<a href="https://docs.google.com/presentation/d/19Z0dEz-_6vgt0S492NjEqfP8nfTKtYjpb8UOfyWfLZ4/edit?usp=sharing">Adding</a> <a href="https://docs.google.com/presentation/d/19Z0dEz-_6vgt0S492NjEqfP8nfTKtYjpb8UOfyWfLZ4/edit?usp=sharing">a</a> <a href="https://docs.google.com/presentation/d/19Z0dEz-_6vgt0S492NjEqfP8nfTKtYjpb8UOfyWfLZ4/edit?usp=sharing">Remote</a> <a href="https://docs.google.com/presentation/d/19Z0dEz-_6vgt0S492NjEqfP8nfTKtYjpb8UOfyWfLZ4/edit?usp=sharing">MySQL</a> <a href="https://docs.google.com/presentation/d/19Z0dEz-_6vgt0S492NjEqfP8nfTKtYjpb8UOfyWfLZ4/edit?usp=sharing">Database</a> <a href="https://docs.google.com/presentation/d/19Z0dEz-_6vgt0S492NjEqfP8nfTKtYjpb8UOfyWfLZ4/edit?usp=sharing">to</a> <a href="https://docs.google.com/presentation/d/19Z0dEz-_6vgt0S492NjEqfP8nfTKtYjpb8UOfyWfLZ4/edit?usp=sharing">a</a> <a href="https://docs.google.com/presentation/d/19Z0dEz-_6vgt0S492NjEqfP8nfTKtYjpb8UOfyWfLZ4/edit?usp=sharing">Spring</a> <a href="https://docs.google.com/presentation/d/19Z0dEz-_6vgt0S492NjEqfP8nfTKtYjpb8UOfyWfLZ4/edit?usp=sharing">Boot</a> <a href="https://docs.google.com/presentation/d/19Z0dEz-_6vgt0S492NjEqfP8nfTKtYjpb8UOfyWfLZ4/edit?usp=sharing">Web</a> <a href="https://docs.google.com/presentation/d/19Z0dEz-_6vgt0S492NjEqfP8nfTKtYjpb8UOfyWfLZ4/edit?usp=sharing">Application</a> <a href="https://docs.google.com/presentation/d/19Z0dEz-_6vgt0S492NjEqfP8nfTKtYjpb8UOfyWfLZ4/edit?usp=sharing">on</a> <a href="https://docs.google.com/presentation/d/19Z0dEz-_6vgt0S492NjEqfP8nfTKtYjpb8UOfyWfLZ4/edit?usp=sharing">Heroku</a>​. The general steps for setting up the environment on Heroku are listed below. Refer to the original documents for more details.

<ol>

 <li>Install <u>​</u><a href="https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html">JDK 8</a>​ or later</li>

 <li>Install <u>​</u><a href="https://maven.apache.org/download.cgi">Apache Maven</a></li>

 <li>Install the ​<a href="https://docs.spring.io/spring-boot/docs/current/reference/html/getting-started-installing-spring-boot.html#getting-started-installing-the-cli">Spring Boot</a>​ framework</li>

 <li>Install <u>​</u><a href="https://dev.mysql.com/downloads/workbench/">MySQL Workbench</a>​ or some other MySQL client</li>

 <li>Create an account on <u>​</u><a href="https://signup.heroku.com/">Heroku</a></li>

 <li>Install the ​<a href="https://devcenter.heroku.com/articles/heroku-cli">Heroku CLI</a></li>

 <li>Create a simple Spring Boot Web application, e.g., spring init –dependencies=web myapp</li>

</ol>




<ol start="8">

 <li>Deploy the Spring Boot application to Heroku, e.g., heroku create</li>

</ol>




<ol start="9">

 <li>Add a MySQL remote database to the remote Spring Boot application on Heroku</li>

 <li>Connect your local MySQL Workbench to the remote MySQL on Heroku</li>

</ol>




Create Remote database on AWS:

This section describes creating a remote MySQL database instance running on AWS.




<ul>

 <li>Login to the Amazon AWS console and expand ​<em>All Services</em>​.</li>

 <li>Under the ​<em>Database</em>​ section, select ​<em>RDS</em>​.</li>

 <li>In the <em>Amazon</em>​ <em> RDS</em> landing page, select <em>Launch</em>​     or ​<em>Get Started Now</em> to add a new RDS instance. If you are on your dashboard, you can choose ​<strong><em>Create Database </em></strong>​</li>

 <li>In the ​<em>Select engine</em>​ screen, select ​<em>MySQL</em>​ and then click ​<em>Next</em>​.</li>

 <li>In the ​<em>Choose use case</em>​ screen, select ​<em>Dev/Test – MySQL</em>​ and then click <em>Next</em>​ ​.</li>

 <li>In the ​<em>Specify DB details</em> screen, keep the default settings, and choose the following configuration and then click ​<em>Next</em>​. Use your own identifier, username, and password. The usernames, names, and identifiers shown in this document are based on a particular course, e.g., ​cs5200​, semeter, e.g., ​Fall2018​, and your lastname, e.g., ​&lt;your lastname&gt;​. Please use your particular values where applicable.

  <ul>

   <li>DB instance class: ​t2.micro</li>

  </ul></li>

</ul>

○    DB instance identifier: ​cs5200-fall2018-&lt;your last name&gt;

○     Master username: ​&lt;choose an username easier to remeber&gt;

○    Master password: ​&lt;Password of your choice.&gt;

○    Confirm password: ​&lt;Password of your choice.&gt;

<strong>Make note of the actual values used above since they will be used in later steps. </strong>

<ul>

 <li>In the ​<em>Configure advanced settings</em> screen, select <em>Yes</em>​ for the ​<em>Public accessibility</em>​. Also, keep the default settings, but choose the name of the database, e.g., cs5200_​ fall2018_&lt;your lastname&gt;​. ​<strong>Note the use of underscores</strong>.​ This will be the name of the schema where tables and their records will be stored. Click on <em>Launch</em>​<em> DB Instance</em> to continue. The database will take a few moments to be created after which you can navigate to it by clicking on ​<em>View DB Instance Details</em> or clicking ​<em>Instances</em> on the left.</li>

 <li>The details screen will be titled with the DB instance identifier chosen earlier, e.g., cs5200-fall2018-&lt;your lastname&gt;​. Scroll down to the ​<em>Connect</em> Make a note of the ​<em>Endpoint</em> since it will be used later to connect remotely to the database. The endpoint is the name of the server machine where the database is running, e.g.,

  <ul>

   <li>Cs5200-spring2018-annunziato.cne500ro4imj.us-west-2.rds.amazon aws.com</li>

  </ul></li>

 <li>Also note the ​<em>Port</em> where the server is listening for incoming connections, e.g., 3306​ .​ If the ​<em>Endpoint</em> is not yet available, wait a few more minutes while the database service is setup.</li>

</ul>




<ul>

 <li>Note that the connection might not be publicly available by default as denoted by the configuration ​<em>Publicly accessible: No​</em>. To make the connection publicly available, under the <em>Security group​</em>, click on the ​<em>Inbound</em> security group. In the security group screen, click the <em>Inbound</em> tab, and then the ​<em>Edit</em> Under the ​<em>Source</em> column, select ​<em>Anywhere</em> from the dropdown, and click ​<em>Save​</em>. Verify that the ​<em>Publicly accessible​</em> setting is set to ​<em>Yes​</em>.</li>

 <li>You can use MySQL workbench to connect to the RDS server using the ○         Hostname: endpoint of the DB instance.

  <ul>

   <li>Username: username chosen in the above steps.</li>

  </ul></li>

</ul>

○ Password: password chosen in the above steps. A Small tutorial on using MySQL workbench can be found here.

<a href="https://docs.google.com/document/d/1hv9-wJv1Y2rTdaQmw4HVACNWsH5D5OfaN-BeVgghrBM/edit?usp=sharing">https://docs.google.com/document/d/1hv9-wJv1Y2rTdaQmw4HVACNWsH5D5OfaN-BeVgghrB </a><a href="https://docs.google.com/document/d/1hv9-wJv1Y2rTdaQmw4HVACNWsH5D5OfaN-BeVgghrBM/edit?usp=sharing">M/edit?usp=sharing</a>




<h1>Create a Schema (15pts.)</h1>

Use SQL to create the following schemas with the properties, data types, and relations as described in the UML class diagram. All tables should define a primary key called “id” configured to auto increment if no value is provided. Foreign keys should have the same name as the table they refer to. Enforce required fields and cardinality. Do not use “enum” to implement the &lt;&lt;enumeration&gt;&gt;. Implement associations between the tables either as primary key/foreign key and/or additional mapping tables, e.g., roles.

<ol>

 <li>(0pts) Create a brand new schema in a remote database hosted on Heroku or AWS. Do all your work in that remote database. As a deliverable, provide the connection string to connect to the remote database which should include the host URL (or IP address), the username and password to login to the database</li>

 <li>(5pts) Create tables ​<strong>person</strong>​, ​<strong>developer</strong>,​ and <strong>user</strong>​ .​ Implement generalization using separate tables for each class, e.g., the ​<strong><em><u>normalized strategy</u></em></strong>​. Name the constraint on the foreign keys using the following pattern: subclass_superclass_generalization, where subclass and superclass are the subclass and superclass in the diagram. For instance if person is a superclass and faculty is a subclass of person, then the foreign key constraint name would be faculty_person_generalization</li>

 <li>(5pts) Create tables website, page, widget, heading, html, youtube, image. Implement generalization using a single table, e.g., the ​<strong><em><u>denormalized strategy</u></em></strong><u>​</u>. Use a new field called DTYPE to discriminate for the type, e.g., WIDGET, HEADING, HTML, YOUTUBE, IMAGE. Use the class name as the values of the field. Default heading size should be 2</li>

 <li>(5pts) Create tables address, phones, website and page roles, and enumerations. If youre database supports “enum”, do not use it. Instead implement enumerations using <a href="https://docs.google.com/presentation/d/1FIcPkKnBDyL-yiopBn-prgeD2moMRwYNwzxiFdKYXkM/edit?usp=sharing">the portable enumeration strategy discussed in class</a>​.</li>

</ol>

<h1>Implement Triggers (15pts.)</h1>

(7pts.) Write a trigger to create ​<strong><em><u>website</u></em></strong><u>​</u> privileges when roles are created for a website, such that all the privileges that apply for a particular role are given to the corresponding user and website.




(8pts.) Write a trigger to create ​<strong><em><u>page</u></em></strong>​ privileges when roles are created for a page, such that all the privileges that apply for that particular role are given to the corresponding user and page.




Use the following roles for the privileges:

<ol>

 <li>owner – create, read, update, delete</li>

 <li>admin – create, read, update, delete</li>

 <li>writer – create, read, update</li>

 <li>editor – read, update</li>

 <li>reviewer – read</li>

</ol>

<h1>Implement Inserts (15pts.)</h1>

Provide SQL queries that insert the data shown below. Note that some will require inserting into more than one table. Use the IDs where provided, otherwise the ID fields should be configured to auto increment. Auto generated IDs can be used where not specified. Nested queries may be used to inquire about previously inserted data. Later inserts can assume data exists from earlier inserts.

<ol>

 <li>(3pts.) Create the following developers and users. Insert into the correct tables depending on the type</li>

</ol>




<table width="759">

 <tbody>

  <tr>

   <td width="36">id</td>

   <td width="82">Username</td>

   <td width="91">Password</td>

   <td width="72">First</td>

   <td width="77">Last</td>

   <td width="111">Type</td>

   <td width="156">Email</td>

   <td width="134">Key</td>

  </tr>

  <tr>

   <td width="36">12</td>

   <td width="82">alice</td>

   <td width="91">alice</td>

   <td width="72">Alice</td>

   <td width="77">Wonder</td>

   <td width="111">Developer</td>

   <td width="156"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="6504090c060025120a0b0100174b060a08">[email protected]</a></td>

   <td width="134">4321rewq</td>

  </tr>

  <tr>

   <td width="36">23</td>

   <td width="82">bob</td>

   <td width="91">bob</td>

   <td width="72">Bob</td>

   <td width="77">Marley</td>

   <td width="111">Developer</td>

   <td width="156"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="ddbfb2bf9db0bcafb1b8a4f3beb2b0">[email protected]</a></td>

   <td width="134">5432trew</td>

  </tr>

  <tr>

   <td width="36">34</td>

   <td width="82">charlie</td>

   <td width="91">charlie</td>

   <td width="72">Charles</td>

   <td width="77">Garcia</td>

   <td width="111">Developer</td>

   <td width="156"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="305358455358705751425359511e535f5d">[email protected]</a></td>

   <td width="134">6543ytre</td>

  </tr>

  <tr>

   <td width="36">45</td>

   <td width="82">dan</td>

   <td width="91">dan</td>

   <td width="72">Dan</td>

   <td width="77">Martin</td>

   <td width="111">User</td>

   <td width="156"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="07636669476a6675736e692964686a">[email protected]</a></td>

   <td width="134">7654fda</td>

  </tr>

  <tr>

   <td width="36">56</td>

   <td width="82">ed</td>

   <td width="91">ed</td>

   <td width="72">Ed</td>

   <td width="77">Karaz</td>

   <td width="111">User</td>

   <td width="156"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="422726022923306c212d2f">[email protected]</a></td>

   <td width="134">5678dfgh</td>

  </tr>

 </tbody>

</table>




<ol start="2">

 <li>(3pts.) Create the following web sites for the developers above. For both the created field and updated field, use the date your assignment will be graded, e.g., do not hardcode it</li>

</ol>




<table width="757">

 <tbody>

  <tr>

   <td width="51">id</td>

   <td width="90">Name</td>

   <td width="243">Description</td>

   <td width="97">Owner</td>

   <td width="94">Editor</td>

   <td width="96">Admin</td>

   <td width="86">Visits</td>

  </tr>

  <tr>

   <td width="51">123</td>

   <td width="90">Facebook</td>

   <td width="243">an online social media and social networking service</td>

   <td width="97">alice</td>

   <td width="94">bob</td>

   <td width="96">charlie</td>

   <td width="86">1234234</td>

  </tr>

  <tr>

   <td width="51">234</td>

   <td width="90">Twitter</td>

   <td width="243">an online news and social networking service</td>

   <td width="97">bob</td>

   <td width="94">charlie</td>

   <td width="96">alice</td>

   <td width="86">4321543</td>

  </tr>

  <tr>

   <td width="51">345</td>

   <td width="90">Wikipedia</td>

   <td width="243">a free online encyclopedia</td>

   <td width="97">charlie</td>

   <td width="94">alice</td>

   <td width="96">bob</td>

   <td width="86">3456654</td>

  </tr>

  <tr>

   <td width="51">456</td>

   <td width="90">CNN</td>

   <td width="243">an American basic cable and satellite television news channel</td>

   <td width="97">alice</td>

   <td width="94">bob</td>

   <td width="96">charlie</td>

   <td width="86">6543345</td>

  </tr>

  <tr>

   <td width="51">567</td>

   <td width="90">CNET</td>

   <td width="243">an American media website that publishes reviews, news, articles, blogs, podcasts and videos on technology and consumer electronics</td>

   <td width="97">bob</td>

   <td width="94">charlie</td>

   <td width="96">alice</td>

   <td width="86">5433455</td>

  </tr>

  <tr>

   <td width="51">678</td>

   <td width="90">Gizmodo</td>

   <td width="243">a design, technology, science and science fiction website that alsowrites articles on politics</td>

   <td width="97">charlie</td>

   <td width="94">alice</td>

   <td width="96">bob</td>

   <td width="86">4322345</td>

  </tr>

 </tbody>

</table>




<ol start="3">

 <li>(3pts.) Create the following pages for the web sites above. Use the semester’s start date for the created field. Use the assignment’s due date for the updated field.</li>

</ol>




<table width="756">

 <tbody>

  <tr>

   <td width="47">id</td>

   <td width="96">Name</td>

   <td width="231">Description</td>

   <td width="91">Website</td>

   <td width="72">Editor</td>

   <td width="82">Reviewer</td>

   <td width="73">Writer</td>

   <td width="64">Views</td>

  </tr>

  <tr>

   <td width="47">123</td>

   <td width="96">Home</td>

   <td width="231">Landing page</td>

   <td width="91">CNET</td>

   <td width="72">alice</td>

   <td width="82">bob</td>

   <td width="73">charlie</td>

   <td width="64">123434</td>

  </tr>

  <tr>

   <td width="47">234</td>

   <td width="96">About</td>

   <td width="231">Website description</td>

   <td width="91">Gizmodo</td>

   <td width="72">bob</td>

   <td width="82">charlie</td>

   <td width="73">alice</td>

   <td width="64">234545</td>

  </tr>

  <tr>

   <td width="47">345</td>

   <td width="96">Contact</td>

   <td width="231">Addresses, phones, and contact info</td>

   <td width="91">Wikipedia</td>

   <td width="72">charlie</td>

   <td width="82">alice</td>

   <td width="73">bob</td>

   <td width="64">345656</td>

  </tr>

  <tr>

   <td width="47">456</td>

   <td width="96">Preferences</td>

   <td width="231">Where users can configure their preferences</td>

   <td width="91">CNN</td>

   <td width="72">alice</td>

   <td width="82">bob</td>

   <td width="73">charlie</td>

   <td width="64">456776</td>

  </tr>

  <tr>

   <td width="47">567</td>

   <td width="96">Profile</td>

   <td width="231">Users can configure their personal information</td>

   <td width="91">CNET</td>

   <td width="72">bob</td>

   <td width="82">charlie</td>

   <td width="73">alice</td>

   <td width="64">567878</td>

  </tr>

 </tbody>

</table>




<ol start="4">

 <li>(3pts.) Create the following widgets for the pages shown.</li>

</ol>




<table width="753">

 <tbody>

  <tr>

   <td width="41">id</td>

   <td width="82">Name</td>

   <td width="68">Type</td>

   <td width="122">Text</td>

   <td width="69">Order</td>

   <td width="131">Width/Height</td>

   <td width="136">Url</td>

   <td width="104">Page</td>

  </tr>

  <tr>

   <td width="41">123</td>

   <td width="82">head123</td>

   <td width="68">heading</td>

   <td width="122">Welcome</td>

   <td width="69">0</td>

   <td width="131">null</td>

   <td width="136">null</td>

   <td width="104">Home</td>

  </tr>

  <tr>

   <td width="41">234</td>

   <td width="82">post234</td>

   <td width="68">html</td>

   <td width="122">&lt;p&gt;Lorem&lt;/p&gt;</td>

   <td width="69">0</td>

   <td width="131">null</td>

   <td width="136">null</td>

   <td width="104">About</td>

  </tr>

  <tr>

   <td width="41">345</td>

   <td width="82">head345</td>

   <td width="68">heading</td>

   <td width="122">Hi</td>

   <td width="69">1</td>

   <td width="131">null</td>

   <td width="136">null</td>

   <td width="104">Contact</td>

  </tr>

  <tr>

   <td width="41">456</td>

   <td width="82">intro456</td>

   <td width="68">html</td>

   <td width="122">&lt;h1&gt;Hi&lt;/h1&gt;</td>

   <td width="69">2</td>

   <td width="131">null</td>

   <td width="136">null</td>

   <td width="104">Contact</td>

  </tr>

  <tr>

   <td width="41">567</td>

   <td width="82">image345</td>

   <td width="68">image</td>

   <td width="122">null</td>

   <td width="69">3</td>

   <td width="131">50×100</td>

   <td width="136">/img/567.png</td>

   <td width="104">Contact</td>

  </tr>

  <tr>

   <td width="41">678</td>

   <td width="82">video456</td>

   <td width="68">youtube</td>

   <td width="122">null</td>

   <td width="69">0</td>

   <td width="131">400×300</td>

   <td width="136">https://youtu.be/h67VX51QXiQ</td>

   <td width="104">Preferences</td>

  </tr>

 </tbody>

</table>




<ol start="5">

 <li>(3pts.) Create the following phones and addresses for the users or developers shown</li>

</ol>




<table width="635">

 <tbody>

  <tr>

   <td width="154"><strong>Username </strong></td>

   <td width="190"><strong>Phones </strong></td>

   <td width="291"><strong>Addresses </strong></td>

  </tr>

  <tr>

   <td width="154">alice</td>

   <td width="190"><strong>123-234-3456</strong>234-345-4566</td>

   <td width="291"><strong>123 Adam St., Alton, 01234</strong>​,234 Birch St. Boston, 02345</td>

  </tr>

  <tr>

   <td width="154">bob</td>

   <td width="190"><strong>345-456-5677 </strong></td>

   <td width="291"><strong>345 Charles St., Chelms, 03455</strong>​,456 Down St., Dalton, 04566,543 East St., Everett, 01112</td>

  </tr>

  <tr>

   <td width="154">charlie</td>

   <td width="190"><strong>321-432-5435</strong>432-432-5433543-543-6544</td>

   <td width="291"><strong>654 Frank St., Foulton, 04322 </strong></td>

  </tr>

 </tbody>

</table>

<h1>Implement View (10pts.)</h1>

Create a view called “deleveloper_roles_and_privileges” that captures a developer’s privileges across all websites and pages. The view should join various tables to capture the developer’s personal information as well as the websites, pages, and their associated roles and privileges. The view should provide the following information:

<ol>

 <li>Developer’s first name</li>

 <li>Developer’s last name</li>

 <li>Developer’s username</li>

 <li>Developer’s email</li>

 <li>Website’s name</li>

 <li>Website’s visits</li>

 <li>Website’s last updated date</li>

 <li>Developer’s role in that website</li>

 <li>Developer’s privileges in that website</li>

 <li>Page’s title</li>

 <li>Page’s views</li>

 <li>Page’s last updated date</li>

 <li>Developer’s role in that page</li>

 <li>Developer’s privileges in that page</li>

</ol>

<h1>Implement Queries (15pts.)</h1>

Write SQL to implement the following queries. Assume the data inserted in the prior problem set. Nested loops may be used.




<ol>

 <li>(3pts.) Retrieve developers

  <ol>

   <li>Retrieve all developers</li>

   <li>Retrieve a developer with id equal to 34 (charlie)</li>

   <li>Retrieve all developers who have a role in Twitter other than owner (charlie, alice)</li>

   <li>Retrieve all developers who are page reviewers of pages with less than 300000 visits (charlie)</li>

   <li>Retrieve the writer developer who added a heading widget to CNET’s home page (charlie)</li>

  </ol></li>

 <li>(3pts.) Retrieve websites

  <ol>

   <li>Retrieve the website with the least number of visits</li>

   <li>Retrieve the name of a website whose id is 678 (Gizmodo)</li>

   <li>Retrieve all websites with videos reviewed by bob (CNN)</li>

   <li>Retrieve all websites where alice is an owner (Facebook, )</li>

   <li>Retrieve all websites where charlie is an admin and get more than 6000000 visits</li>

  </ol></li>

 <li>(3pts.) Retrieve pages

  <ol>

   <li>Retrieve the page with the most number of views</li>

   <li>Retrieve the title of a page whose id is 234</li>

   <li>Retrieve all pages where alice is an editor (About)</li>

   <li>Retrieve the total number of pageviews in CNET</li>

   <li>Retrieve the average number of page views in the Web site Wikipedia</li>

  </ol></li>

 <li>(3pts.) Retrieve widgets

  <ol>

   <li>Retrieve all widgets in CNET’s Home page</li>

   <li>Retrieve all youtube widgets in CNN</li>

   <li>Retrieve all image widgets on pages reviewed by Alice</li>

   <li>Retrieve how many widgets are in Wikipedia</li>

  </ol></li>

 <li>(3pts.) To verify the page and website triggers written earlier function properly:

  <ol>

   <li>Retrieve the names of all the websites where Bob has DELETE privileges. Answer: Twitter, Wikipedia, CNET, Gizmodo (where Bob has either owner or admin roles).</li>

   <li>Retrieve the names of all the pages where Charlie has CREATE privileges. Answer: Home, Preferences (where Charlie has Writer role)</li>

  </ol></li>

</ol>

<h1>Implement Updates (15pts.)</h1>

<ol>

 <li>(3pts.) Update developer – Update Charlie’s primary phone number to 333-444-5555</li>

 <li>(3pts.) Update widget – Update the relative order of widget head345 on the page so that it’s new order is 3. Note that the other widget’s order needs to update as well</li>

 <li>(4pts.) Update page – Append ‘CNET – ‘ to the beginning of all CNET’s page titles</li>

 <li>(5pts.) Update roles – Swap Charlie’s and Bob’s role in CNET’s Home page</li>

</ol>

<h1>Implement Deletes (15pts.)</h1>

<ol>

 <li>(3pts.) Delete developer – Delete Alice’s primary address</li>

 <li>(3pts.) Delete widget – Remove the last widget in the Contact page. The last widget is the one with the highest value in the order field</li>

 <li>(4pts.) Delete page – Remove the last updated page in Wikipedia</li>

 <li>(5pts.) Delete website – Remove the CNET web site, as well as all related roles and privileges relating developers to the Website and Pages</li>

</ol>

<h1>Deliverables</h1>

As a deliverable, Please fill the details in the “Submission.txt” that will be shared with you in your github profiles. Key items to submit are:

<ul>

 <li>the connection string for you remote database</li>

 <li>the hostname,</li>

 <li>username and</li>

 <li>password,</li>

 <li>port</li>

</ul>




On Heroku, the connection string can be found in the Settings section of your dashboard. Click on Reveal Config Vars. Copy the environment variable labeled CLEARDB_DATABASE_URL and submit it on Blackboard




On AWS, click on your database identifier and in the ​<em>Connect</em>​ tab, you would find the endpoint(hostname) and port of your DB. Submit them along with your username and password.


