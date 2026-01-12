# Document360 
Document360 is a full-featured, hosted knowledge base platform designed for creating, managing, and publishing both internal and external user documentation. 

- GitHub Repo as Storage: No, not as its primary storage. Document360 stores your content in its own cloud-based database (MongoDB/Azure Blob Storage).
- Workflow: It provides a user-friendly, web-based editor (which supports Markdown) and a more traditional content management system (CMS) experience with features like versioning, analytics, and a homepage builder.
- GitHub Integration: It offers an integration with GitHub that allows for a one-way sync of Markdown files from a GitHub repository into Document360. The synced articles are read-only within Document360's editor; any changes must be made in the source GitHub repository and then synced back.

Best for: Teams where technical writers and non-developers are primary content creators, who prefer a polished UI and dedicated documentation features (like analytics, detailed access control, etc.), but still want the content source to originate from a GitHub repo. 