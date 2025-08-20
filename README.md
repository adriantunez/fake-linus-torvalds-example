# Fake Linus Torvalds Example  

This repository is an example used and explained in the blog post: [**"Git signed commits"**](https://adriantunez.cloud/posts/git-signed-commits/).  

The blog post demonstrates how unsigned commits can be misleading by showing an example commit by impersonating **Linus Torvalds** (this public repository).  

> **Important note:**
> Linus Torvalds has absolutely no connection to this repository.  
> The commit attributed to him is **fake and purely educational**, it's only used to illustrate the risks of unsigned Git commits.  

## Why this repository exists  

Git allows you to set arbitrary author information. Without verification mechanisms in place, anyone can impersonate someone else.  

This repo showcases that problem, through several commit use cases. Making easier to understand why signed commits matter, specially in open-source or security-focused companies.

For a deeper explanation, see the original blog post: [**"Git signed commits"**](https://adriantunez.cloud/posts/git-signed-commits/)  

## Key Takeaways  

- Author fields in Git commits are **not inherently trustworthy**.  
- Signed commits help establish **authenticity and trust**.  
- There are different encryption keys, we've seen **GPG** and **SSH**.  
- GitHub rulesets enforcement provides an **automated and secure way to enforce trust**.
- This repository is only for **educational and demonstration purposes**.  

## Contact  

If you have any questions, feel free to reach out:  

- Blog: [adriantunez.cloud](https://adriantunez.cloud/contact/)
- GitHub: [@adriantunez](https://github.com/adriantunez)
- LinkedIn: [adriantunez](https://www.linkedin.com/in/adriantunez/)
