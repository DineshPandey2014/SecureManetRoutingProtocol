SecureManetRoutingProtocol
==========================

Team_26


CONTENTS
I.	HOW TO START THE App
II. HOW TO USE THE APP
III. Software Requirements
IV. Browser Supported
V. App deployment.

I. HOW TO START THE App.
Windows/Macintosh/Linux/AWS

1. Run nodeOne.js   (# Sender node)
2. Run nodeThree.js (# Destination node)
3. Run nodeFour.js  (# Intermediate node)
4. Run nodeTwo.js   (# Intermediate node)

II. HOW TO USE THE APP
1. How to access the NodeOne: URL:http://IPADDRESS:3000/
   Enter the data in the sender node text area.
   Press the button send.
   Refresh the page, you will see the acknowledgment. Success or Error
   Success: Means data is send successfully from NodeOne to NodeThree via NodeTwo
   Error: Here node four will hack the data which we send from NodeOne to NodeThree via NodeFour.      
2. How to access the NodeThree: URL:http://IPADDRESS:2000/
   NodeThree will receive the data from NodeOne via intermediate node (NodeTwo, NodeFour).
3. NodeTwo will act as intermediate node there is no UI, only server side code.
4. NodeFour will act as intermediate node there is no UI only server side code.

III  Software Requirements

1. Node.js Download Link: http://nodejs.org/
2. Install npm and node using the node.js installer.
3. npm install express
4. npm install ejs
5. npm install crypto
6. npm install body-parser
7. npm install mongoose
8. npm install trim
9. Install mongo DB LINK http://docs.mongodb.org/manual/tutorial/install-mongodb-on-windows/#install-mongodb


IV.  Browser Supported
1. All browser are supported.

V  App deployment.

1. Tested in AWS
2. Hotspot
3. Private network.
