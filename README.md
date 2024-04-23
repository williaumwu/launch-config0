Launch Configuration repository contain sample __config0/config.yml__ files.

 - The branches correspond to sample automations.
 - Each branch contains a sample launch yml – e.g. config0/config0.yml
   - For example, branch mongodb contains a sample config0/config0.yml to create and launch a MongoDb replica set on ec2.
 - First, run and execute *vpc* branch. The vpc is used by other automations like MongoDb and Codebuild CI. 
 - Second, run and execute *vars_set* branch. This creates a variables set where other automations can select and have variable substitution.
