**Don't despair. Flexpair!**
[![](assets/architecture.png)](http://demo.flexpair.com){:target="_blank"}

## Seamless transitions between synch and asynch

The success of data-driven projects hinges on efficiently sharing work packages between coworkers and jointly delivering them to the client.

With more and more companies transitioning into a hybrid work model, we asked ourselves the question: How can we make those frequent handovers more consistent and a truly hands-on experience?

## Consistently reproducible work environment


The solution we came up with during 2020/21 Corona short-time work is called **Flexpair**. Now, what does it actually mean

<dl>
  <dt><strong>to flexpair (verb)</strong></dt>
  <dd>to cowork and innovate across organizations and timezones, as immediate as sitting next to each other shoulder to shoulder, suitable for Linux affine STEM professionals and data scientists in particular</dd>
  <dt><strong>Flexpair (noun)</strong></dt>
  <dd>flexibly scalable and reproducible shared desktop and communication infrastructure, which is not only capable of multi-cloud deployment but also puts emphasis on privacy and environmental friendliness</dd>
</dl>

## Taking privacy and data protection serious

 No surprise Flexpair simply rocks, being rock-solid <u>and</u> flexible in just the right places. Because it was tailor-made by experienced data scientists to be enjoyable for their fellow data nerds. Hence, it has all the features that your prospective high potentials value most, like
- **r**eproducibility
- **o**pen-source
- **c**lean interface
- **k**now where your data resides
- **s**calable compute power 

Take a free look at our [demo environment here](http://demo.flexpair.com){:target="_blank"}. Or learn a bit more about our values and the technical features of our product below.

## Save money and the planet, there's no contradiction

To enable effective and inclusive remote work that contributes to 
1. a fair distribution of intellectual property
2. a significant reduction in global CO2 emissions

Most notably, project members will have no need for a second or third notebook anymore.

Not so fun fact: Did you know that the production of a notebook until you switch it on the first time produces as much CO2 as driving about 1200 km with your car?

## Tech Features

Flexpair is a collection of Terraform modules and cloud-init scripts for deploying a shared Ubuntu desktop with built-in high quality audio conferencing and self-hosted team inbox to an arbitrary public cloud account. Free tier resources are sufficient and multi-cloud is actively supported.

![](assets/screenshots.gif)

- Ubuntu 20.04 LTS with lightweight LXQt desktop
  - Requires only 1 GB of RAM (often available for free)
- Infrastructure-as-code powered by Terraform Cloud
  - the option to flexibly scale up (and down) your RAM and CPU cores
  - the ability to clone not only the code but the entire shared desktop at the press of a button
  - no missing dependencies etc. ever again, even across different cloud providers
- Apache Guacamole for screen and Mumble for audio
  - minimal latency and bandwidth requirements
- Receive a dedicated subdomain or bring your own
- self-hosted team inbox [subdomain]@flexpair.com
  - a unified tool for synchronous and asynchronous collaboration
- SSH encryption and TLS certificate for protecting your data
- full control over where your data are stored
- data privacy by locking out data collectors
- zero install, fully runs in your favorite browser and hence
  - zero friction when you need external people like freelancers to join your project ad hoc

# When Not to use Flexpair

If you really need to give someone remote access to your local machine, please consider using [TeamViewer](https://www.teamviewer.com/en/) or comparable established solutions.

Also, Flexpair deliberately does not offer video conferencing.

