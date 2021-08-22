The success of data-driven projects hinges on efficiently sharing work packages between coworkers and jointly delivering them to the client.

With more and more companies transitioning into a hybrid work model, we asked ourselves the question: How can we make those frequent handovers more consistent and a truly hands-on experience?

# Value Proposition

Flexpair is a cloud environment for shoulder-to-shoulder-like remote collaboration of data-driven high potentials. And it has all the features that this target group values most, like

- **r**eproducibility
- **o**pen-source
- **c**lean interface
- **k**now where your data resides
- **s**calable compute power

 No surprise Flexpair simply rocks, because it was tailor-made by experienced data scientists to be enjoyable for their fellow data people.

<dl>
  <dt><strong>to flexpair (verb)</strong></dt>
  <dd>to cowork and innovate across organizations and timezones in a truly hands-on fashion, in particular among STEM professionals</dd>
  <dt><strong>Flexpair (noun)</strong></dt>
  <dd>flexibly scalable and reproducible shared desktop and communication infrastrucure, privacy-friendly and multi-cloud enabled</dd>
</dl>

Take a free look at our [demo environment here](http://demo.flexpair.com){:target="_blank"}. Or learn a bit more about our values and the technical features of our product below.

![](architecture.png)

# Mission Statement

To enable effective and inclusive remote work that contributes to 
1. a fair distribution of intellectual property
2. a significant reduction in global CO2 emissions

With our novel Flexpair solution, you will have
- the feeling of shoulder-to-shoulder pair programming, even when working remotely
- a unified tool for synchronous and asynchronous collaboration
- zero friction when you need external people like freelancers to join your project ad hoc
- the ability to clone not only the code but the entire shared desktop at the press of a button
- no missing dependencies etc. ever again, even across different cloud providers
- the option to flexibly scale up (and down) your RAM and CPU cores
- minimal latency and bandwidth requirements
- no need for a second or third notebook

Not so fun fact: Did you know that the production of a notebook until you switch it on the first time produces as much CO2 as driving about 1200 km with your car?

# Tech Features

Flexpair is a collection of Terraform modules and cloud-init scripts for deploying a shared Ubuntu desktop with built-in high quality audio conferencing and self-hosted team inbox to an arbitrary public cloud account. Free tier resources are sufficient and multicloud is actively supported.

- Ubuntu 20.04 LTS with lightweight LXQt desktop
- Requires only 1 GB of RAM (often available for free)
- Infrastructure-as-code powered by Terraform Cloud
- Apache Guacamole for screen and Mumble for audio
- Receive a dedicated subdomain or bring your own
- self-hosted team inbox [subdomain]@flexpair.com
- SSH and TLS certificate for protecting your data
- full control over where your data are stored
- data privacy by locking out data collectors
- zero install, fully runs in your favorite browser

### When not to use Flexpair

The least thing we want is to waste your precious time. Therefore, please do not read any further

- if you really need to give someone remote access to your local machine, please consider using [TeamViewer](https://www.teamviewer.com/en/) or comparable established solutions

In any other case, we would love to have you as our valued customer.

