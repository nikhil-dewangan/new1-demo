# new1-demo
This is demo for Git &amp; GitHub Class for new1-demo repository.
A repository (or repo) is a central location where all the files related to a project are stored. 
It also tracks the history of changes made to these files. Think of it as a project's folder that, 
Git manages to keep everything organized and version-controlled.


#git config --global user.name "Your Name"
#git config --global user.email "your.email@example.com"

Verifying a JWT:
jwt.verify(token, secretKey, (err, decoded) => {
  if (err) {
    console.log('Token is invalid or expired');
  } else {
    console.log('Token is valid', decoded);
  }
});

app.put('/users/:id', (req, res) => {
  const user = users.find(u => u.id === parseInt(req.params.id));
  if (!user) return res.status(404).send('User not found');
  user.name = req.body.name;
  res.json(user);
});
Define Endpoints: Decide what functionality your API will provide and define the endpoints.
. Set Up a Server: Use a framework (e.g., Express.js for Node.js) to create a server that handles requests and responses.
. Handle Requests: Write code to handle each type of request (GET, POST, etc.) and interact with your data source.
. Send Responses: Ensure your API sends back the appropriate status codes and data.
