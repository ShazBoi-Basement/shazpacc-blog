+++
title = "How to Make Post"
date = "2022-01-17T14:08:42+05:30"
author = "itspacchu"
authorTwitter = "" #do not include @
cover = ""
tags = ["How to", "Tutorial"]
keywords = ["Tutorial"]
description = "How to add posts to this blog through github"
showFullContent = false
+++

 Hello everyone this is a tutorial on how to post to this blog so this blog is a something called as get of actions which kind of automatically does all the processing of making HTML files so basically all we need to do is make a markdown file.

 First you need to clone the repo of this blog.

[![img](https://i.imgur.com/w0XQIp1.png)](https://github.com/ShazBoi-Basement/shazpacc-blog)

```git clone https://github.com/ShazBoi-Basement/shazpacc-blog```

Now you need to go into a folder called content and inside that folder you need to make a folder called posts.
    
![img](https://i.imgur.com/sRzWCy1.png)

Make a new ```post-name.md``` file using this template below

{{< code language="markdown" title="Post template" id="1" expand="Show" collapse="Hide" isCollapsed="true" >}}
+++
title = "Post Title"
date = "Date"
author = "Author"
authorTwitter = "" #do not include @
cover = ""
tags = ["", ""]
keywords = [""]
description = ""
showFullContent = false
+++


Post content here

{{< /code >}}

After modifying you can commit changes and push to github.
You might have to create a fork of the repository and then push the changes to the original branch where the repository is hosted one of the administrator or maintainers are going to approve the changes and they are going to be added to the blog.

Cheers :D