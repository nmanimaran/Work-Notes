
So maybe with the sandbox skill, we have it so that when the sandbox deploy happens, there is a document called pending deploy features which states what feature is in sandbox that isn't in a prod and what are the pre-reqs. 

Then we have a promote prod skill which promotes to prod, but also looks at that documents, takes those pre-reqs in mind, and then also creates a document called release notes. This way, I don't have to constantly remember the features I just deployed.