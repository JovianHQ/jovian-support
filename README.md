# Jovian

Jovian is a platform for sharing and collaborating on Jupyter notebooks. You can learn more on https://www.jvn.io . This repository serves as a public roadmap and bug tracker for Jovian. Visit the issues to page to report bugs, propose new features and discuss existing ones: https://github.com/swiftace-ai/jovian-support/issues. 

# Getting started with Jovian

Install the `jovian` python library.

```py
  pip install jovian --upgrade
```

Import the library into a Jupyter notebook.

```py
  import jovian
```

Use the `commit` command to capture and upload the Jupyter notebook and Python environment (Anaconda or pip).

```py
  jovian.commit()
```

You’ll be prompted for an API key, which you can generate by logging in here: https://jvn.io/login .

Once the notebook is uploaded successfully, you will get a shareable link to it. Other users can comment on parts of the notebook, and you'll get email notifications when they comment.

For feedback, suggestions and feature requests, drop us a line at hello@jvn.io .
