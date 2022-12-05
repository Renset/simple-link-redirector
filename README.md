# Simple RDP link redirector

Simple RDP link redirector is an easy-to-use lightweight tool (2.79KB) to provide redirection to RDP (Remote Desktop) URL.

## Motivation

While working with some tools like Notion, you may notice that rdp links and/or files couldn't be used directly. You can use this simple and very lightweight tool to redirect directly to the provided RDP link or even download an .rdp file.

## Features
- Redirect to the provided URL
- Create an .rdp file from the provided RDP link
- The window is automatically closing after performing redirect or download

## Usage example
### Using GitHub pages (the easiest way)
- Redirect to RDP link: https://renset.github.io/simple-rdp-link-redirector/?rdp://full%20address=s:exampleserver:3389
- Download as an .rdp file: https://renset.github.io/simple-rdp-link-redirector/?file=rdp://full%20address=s:exampleserver:3389

### Deploying in your own environment
- Redirect to RDP link: https://**%your-redirector-path%**?rdp://full%20address=s:exampleserver:3389
- Download as an .rdp file: https://**%your-redirector-path%**?file=rdp://full%20address=s:exampleserver:3389

## Security
No data is stored anywhere on 3rd party servers since the redirector works only on the browser side. However don't forget to use it with an HTTPS protocol while deploying in your own environment.
