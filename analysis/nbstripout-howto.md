
It is advisable to remove the output of the notebook before committing any changes. This approach has several advantages, such as reducing the size of the notebook files, allowing git to track only code modifications, and preventing data from being stored in the repository as output. To achieve this, the repository is configured to utilize [nbstripout](https://github.com/kynan/nbstripout).
The functionality can be enabled and disabled by running the following commands:
```
nbstripout --install
```
```
nbstripout --uninstall
```