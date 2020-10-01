# ColabCode

Run code server on Google Colab or Kaggle Notebooks

- install colabcode: `pip install colabcode`
- import colabcode: `from colabcode import ColabCode`
- run: `ColabCode(port=10000, password="abhishek")`
- you can also run it with any password or port :)
Approach 1: Python PackagePermalink
In this setup, we use the colab-code package that automates all the manual setup steps previously described in the Approach 2 section of this blog post. You can make a copy of this notebook directly to get started.

First, install the colab-code package using the following command:

 pip install colabcode
Now, import ColabCode class from the package and specify the port and password.

 from colabcode import ColabCode
 ColabCode(port=10000, password="password123")
You can also use it directly with the default port and without any password as shown below.

 from colabcode import ColabCode
 ColabCode()
You will get the ngrok URL in the output. Click the link and a login page will open in a new tab.



Type the password you had set in step 2 and click submit. If the page gets stuck for more than 4-5 seconds, refresh the page and you should be redirected to the editor.



Now you will get access to the editor interface and can use it to work on python files.

