# Ansible Project Details:

## 1- Create your first role with name (web)

## 2- The task book will include:

- **Installing a package**

```
    (Get the package name from vars)
```

- **Copying a file from controller to host using template**

```
    (Get the template name & template message from vars)
    (The actual template file will be stored in ./roles/web/templates)
    (Will also notify the restart handler)
```

- **Copying a list of files from controller to host using loop**

```
    (Get the list of file names from vars)
    (The actual files will be stored in ./roles/web/files)
    (Will be executed using handlers)
```

- **Restart the service of the installed package**

```
    (Will be executed using handlers chaining)
```
