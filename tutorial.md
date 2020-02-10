# Cloud Shell Walkthrough

## Introduction

### Description

Hello Cloud Shell Walkthrough.

### References

1. [walkthrough tutorial](https://cloud.google.com/shell/docs/walkthroughs)
2. [walkthrough markdown reference](https://cloud.google.com/shell/docs/walkthrough-markdown-reference)

### Other tutorials

1. [cloud shell tutorial](https://github.com/GoogleCloudPlatform/cloud-shell-tutorials)
2. [spinnaker for google cloud platform](https://console.cloud.google.com/marketplace/details/google-cloud-platform/spinnaker)

## Demo 1 - code snippet

```bash
gcloud auth list
```

NOTE: The resulting code snippet comes with a copy-to-clipboard button in the right-hand corner.

## Demo 2a - project setup

<walkthrough-project-setup permissions="compute.instances.create"></walkthrough-project-setup>

## Demo 2b - project and billing setup

<walkthrough-project-billing-setup permissions="compute.instances.create"></walkthrough-project-billing-setup>

## Demo 3 - enable apis

NOTE: Not working yet. Still trying to figure out the right way.

<walkthrough-enable-apis apis="compute.googleapis.com,stackdriver.googleapis.com,vision.googleapis.com"></walkthrough-enable-apis>

### Other tutorials

1. https://raw.githubusercontent.com/GoogleCloudPlatform/cloud-shell-tutorials/master/cloud-console-tutorials/python_vision_quickstart/python_vision_quickstart.md

## Demo 4 - open file

e.g., open and edit the file "~/cloudshell_open/cloudshell-walkthrough/README.md"

<walkthrough-editor-open-file filePath="cloudshell_open/cloudshell-walkthrough/README.md" 
                              text="README.md">
</walkthrough-editor-open-file>

## Demo 5 - spotlights and buttons

### 5a inline icons

All failed except `web-preview`.

<walkthrough-cloud-shell-icon></walkthrough-cloud-shell-icon>
<walkthrough-web-preview-icon></walkthrough-web-preview-icon>
<walkthrough-cloud-shell-editor-icon></walkthrough-cloud-shell-editor-icon>
<walkthrough-nav-menu-icon></walkthrough-nav-menu-icon>
<walkthrough-notification-menu-icon></walkthrough-notification-menu-icon>
<walkthrough-pin-section-icon></walkthrough-pin-section-icon>
<walkthrough-conclusion-trophy></walkthrough-conclusion-trophy>

### 5b spotlight-pointer

All failed.

<walkthrough-spotlight-pointer spotlightId="console-nav-menu"
                               text="console-nav-menu">
</walkthrough-spotlight-pointer>

<walkthrough-spotlight-pointer spotlightId="devshell-activate-button"
                               text="devshell-activate-button">
</walkthrough-spotlight-pointer>

<walkthrough-spotlight-pointer spotlightId="devshell-web-editor-button"
                               text="devshell-web-editor-button">
</walkthrough-spotlight-pointer>

<walkthrough-spotlight-pointer spotlightId="devshell-web-preview-button"
                               text="devshell-web-preview-button">
</walkthrough-spotlight-pointer>

### 5c open-cloud-shell-button

Ok. A new cloud shell tab will be opened.

<walkthrough-open-cloud-shell-button></walkthrough-open-cloud-shell-button>

### 5d editor-spotlight

Ok.

<walkthrough-editor-spotlight spotlightId="fileMenu">file menu</walkthrough-editor-spotlight>

### Other tutorials

1. https://raw.githubusercontent.com/GoogleCloudPlatform/cloud-shell-tutorials/master/cloud-console-tutorials/storage_quickstart/storage_quickstart.md

## Demo 6 data binding

<walkthrough-watcher-constant key="my-key" value="Hello Google"></walkthrough-watcher-constant>

My custom key "my-key" and value "{{my-key}}"

Built-in key "project-id" and value "{{project-id}}"

Built-in key "project-name" and value "{{project-name}}"

## Conclusion

Done!
