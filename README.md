## What happened to the code?
[Amazon Web Services](http://aws.amazon.com/) is moving our GitHub hosted repositories to a new
GitHub organization: <http://github.com/aws>. Nothing is lost. Only moved.

## What do I do now?
If you have no outstanding changes, simply update the URL of the repository's origin:

- Change the origin URL of the repository: git remote set-url origin git@github.com:aws/aws-sdk-ios.git
- Verify the remote is correct: git remote -v
- Lastly, rename your local diretory to match new name: mv aws-sdk-for-ios aws-sdk-ios

If you have outstanding changes, you'll next want to:

