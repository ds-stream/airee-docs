# Contributing to Airee
Thank you for your interest in contributing! Contribution guidelines are listed below. If you're unsure about how to start contributing please contact us via email: [airee.contact@dsstream.com](mailto:airee.contact@dsstream.com) 

## Code of conduct
Please follow our [Code of conduct](CODE_OF_CONDUCT.md) in the context of any contributions made to Airee.

## Airee specification
Before you can start contributing, you need to understand how our product is build, it is simple one so it won’t take you long 
to read the [docs](https://github.com/ds-stream/Airee-docs)🙂

## Areas for contributing
We gladly welcome all improvements existing on the codebase. 

#### 1. Open an issue, or find a similar one.
Before jumping into the code please first:
1. Verify if an existing [GitHub issue](https://github.com/ds-stream/Airee-docs/issues) matches your contribution.
2. If you don't find an existing issue, [please create a new one](https://github.com/ds-stream/Airee-docs/issues/new/choose) to explain what you want to achieve.
3. Assign the issue to yourself and add a comment to tell that you want to work on this.

This will enable our team to make sure your contribution does not overlap with existing works.

#### 2. Let's code
1. Fork our GitHub repositories:  
   For changes in core application:  
   [Airee controller](https://github.com/ds-stream/airee-controller)  
   [Template infra](https://github.com/ds-stream/template_infra_dev)  
   [Template app](https://github.com/ds-stream/template_app_dev)  
   [Template workspace data](https://github.com/ds-stream/template_workspace_data_dev)
   
   For changes in runner:<br>
   [Airee runner](https://github.com/ds-stream/runner-container)
   
   For changes in monitoring:<br>
   [Airee monitoring]()
   
3. Open a branch for your work. Please remember to sustain the same branch names between template repositories, thanks to that you will be able to easily test the whole process using _-b_ flag in controller app.
4. Code, and please write **tests**.
5. Ensure all tests pass.  
6. Please remember to update documentation in Airee-docs repo.

#### 3. Open a pull request
1. Rebase master with your branch before submitting a pull request.
2. Open the pull request.
   Please create descriptive title for PR with reference to GitHub issue.  
   Examples:  
    #7 pause/unpuse command added to controller  
    #15 fix for check name length function  
3. Wait for a review from our team.

### **Documentation**
Our goal is to keep our docs comprehensive and updated. If you would like to help us in doing so, we are grateful for any kind of contribution:

* Report missing content
* Fix errors in existing docs
* Help us in adding to the docs

Our docs can be found [here](https://github.com/ds-stream/Airee-docs)

### **Requesting new features**
To request new features, please create an issue on this project.
If you would like to suggest a new feature, we ask that you please use our issue template. 
It contains a few essential questions that help us understand the problem you are looking to solve and how you think your recommendation will address it.

### **Reporting bugs**
**‌**Bug reports help us make Airee better for everyone. We provide a preconfigured template for bugs to let you know what information we need.
Please do not create a public GitHub issue. If you've found a security issue, please email us directly at [airee.security@dsstream.com](mailto:airee.security@dsstream.com) instead of raising an issue.
