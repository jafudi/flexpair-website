We aim at three overarching goals:

1. Meaningful hybrid data science
2. Diversity, equity and inclusion
3. Preserving our beautiful planet

by following clear design principles:

1. Make everything reproducible → *cloud infrastructure, installed software, knowledge transfer*
2. Provide secure and easy access → *strong encryption, zero local install, respect for privacy*
3. Minimize the use of resources → *RAM and band width requirements, no duplicate hardware*

![High-level illustration of the Flexpair architecture](assets/architecture.png)
## Problem

Data science has become location-independent. Still it is lacking a meaningful integration of synchronous and asynchronous work steps in one tool.

1. most data science applications are evaluated and eventually approved by the customer based on visualizations and using real data
2. CI/CD pipelines usually contain neither significant amounts of real data nor visualizations for technical and runtime reasons and due to data protection.
3. workarounds like testing on local machines and traditional screen sharing do not solve the problem, as these individual development environments are neither identical to each other nor to the production environment (dependencies etc.)
4. Even if a dedicated (shared) staging environment exists, it is often used only for the master branch and thus far too rarely or late in the process. Nevertheless, financial and environmental fixed costs are constantly incurred.
5. The problem existed before Corona, and it does not get easier in a hybrid work context. But hybrid is good for inclusion and the environment. And as more and more companies transition to a hybrid working model, we asked ourselves the question: How can we make those frequent handovers more consistent and a truly hands-on experience?

<!-- Nach dem Intro geht es normalerweise um das Problem, was euer Produkt oder eure Dienstleistung für einen potenziellen Markt löst. Vermeidet hier komplizierte Formulierungen oder diskutable Argumente. In der Regel sind drei sehr klare und unwiderlegbare Aussagen völlig ausreichend. Lasst keine Zweifel aufkommen und formuliert diese Folie so, dass jeder das Problem nachvollziehen kann. -->

## Solution

1. Automatically create an identical clone of a standardized staging environment whenever opening a merge request for a feature branch. 
2. Have automated CI/CD run in the created staging environment
3. Schedule an interactive live review session with one of your peers, where you both access the staging environment over the web
4. After the merge, tear down the environment automatically.

<!-- Für jedes Problem, das ihr in eurem Pitch Deck aufzeigt, solltet ihr auch schlagkräftige Lösungen präsentieren. Diese Folie muss so konzipiert sein, dass ihr schnell und verständlich den Nutzen eures Produktes oder eurer Dienstleistung kommunizieren könnt. Auf diese Weise solltet ihr ebenfalls sehr klare Aussagen darüber treffen, wie die zuvor dargestellten Problemen durch eure Technologie gelöst werden. Keine Verkomplizierung! Haltet es einfach und auf den Punkt! -->

## Product Demo

[Link to demo](http://demo.flexpair.com)

Include screenshots.

<!-- Falls ihr schon einen ersten Prototypen, Klick-Dummy oder sonstiges Vorzeigbares habt – her damit! Es ist immer sinnvoll Bilder oder Videos eures Produktes zu zeigen, um eure Lösung und euren Nutzen zu verdeutlichen und mögliche Zweifel zu eliminieren. Hebt die Produkteigenschaften hervor, hinterlasst bleibenden Eindruck und – noch wichtiger – Verständnis für eure Idee. -->

## Market Size

<!-- ### Nice Class 9 (Software)
Computer programs for connecting remotely to computers or computer networks;
Cloud computing software;
Collaboration software; Real-Time Collaborative Editing [RTCE] platforms [software];
Development environment software;
Software for arranging online transactions;

### Nice Class 38 (Telecommunication Services):
Teleconferencing services;
Electronic messaging services;
Providing online facilities for real-time interaction with other computer users;
Providing user access to platforms on the Internet;

### Nice Class 42 (IT Services):
Rental, installation and configuration of computer software; Configuration of computer networks using software; Updating and adapting of computer programs according to user requirements;
Computer software consultancy; Advisory services in the field of product development and quality improvement of software; Computer system design using agile development methods;
Platform as a service [PaaS]; Software as a service [SaaS];
Configuration of computer networks using software;
Hosting online facilities for conducting interactive discussions;
Cloud computing; Providing virtual computer systems and virtual computer environments through cloud computing;
Providing temporary use of web-based applications; -->

According to a [press release from Gartner in July 2020](https://www.gartner.com/en/newsroom/press-releases/2020-07-23-gartner-forecasts-worldwide-public-cloud-revenue-to-grow-6point3-percent-in-2020) the market demand for cloud-based desktop-as-a-service (DaaS) will rise to 2.535 billion USD in 2022. This consitutes the Total Addressable Market (TAM) which is, of course, totally unrealistic to achieve with our product in the near future.

We deliberately chose to focus on Linux as our guest operating system for a variety of reasons that software developers in particular will immediately understand. In order to quantify the preference for UNIX-based operating systems over Windows, we analyzed the raw data from [Stack Overflow's 2020 user survey](https://insights.stackoverflow.com/survey/2020) and found that 23.2% of professional developers are already using Linux as their primary desktop, 25.0% were on MacOS and 16.0% were Windows users explicitely stating that they would rather prefer to work on Linux. Extrapolating from the 64462 valid responses to the survey, we are confident to conclude that 64.3% of global pro-developers are affine to UNIX and would dislike being forced to use Windows on a virtual desktop.

But also people working in other sectors like education and media as well as finance value the security and stability of Linux. A whopping 16.9% of all Ubuntu users work in finance according to [21,291 survey responses in April 2020](https://ubuntu.com/blog/ubuntu-20-04-survey-results). These verticals on top of IT add up to a little over 50% of the whole market according to [Marketysers Global Reports And Data](https://www.reportsanddata.com/report-detail/desktop-virtualization-market). Considering that there are some Linux users in the other half of verticals as well, we consider a Servicable Adressable Market (SAM) of around 0.500 x 0,643 x TAM not as an overestimate. For the year 2022 this means we expect 815 million USD or 675 million EUR demand for LINUX-based DaaS solutions.

Finally, the Servicable Obtainable Market (SOM) is likely the small and medium size businesses (about 20% of the market), as the more established [competitors](https://www.g2.com/products/shells-com/competitors/alternatives) catering to large enterprises come with a hefty price tag.

<!-- Die Folie über eure potenzielle Marktgröße ist enorm wichtig, denn sie gibt uns erste Eindrücke darüber, wie ihr eure Geschäfts- und Wachstumsmöglichkeiten einschätzt. Es gibt hier verschiedenste Möglichkeiten eure Marktanalyse darzustellen. Ob Bottom Up, Top Down, TAM, SAM, SOM oder Szenario-Analysen – eurer Kreativität sind hier keine Grenzen gesetzt. Wichtig ist, dass die Größe eures Zielmarktes realistisch berechnet ist und das damit verbundene Potential ersichtlich wird. -->

## Business Model


<!-- Die Zahlen sind das Herzstück eures Pitch Decks, daher solltet ihr hier nachvollziehbare Annahmen über euren Business Case liefern. Euer Erlösmodell in einfachen Worten zu präsentieren ist mit Sicherheit nicht die einfachste Aufgabe – schon gar nicht ohne euer verbales Zutun.  Macht verständlich, wie euer Startup funktioniert und ihr Geld verdienen wollt. -->

## Competition

<!-- https://www.tablesgenerator.com -->
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-bobw{font-weight:bold;text-align:center;vertical-align:bottom}
.tg .tg-18q7{background-color:#70AD47;text-align:center;vertical-align:bottom}
.tg .tg-31j1{background-color:#FFC000;text-align:center;vertical-align:bottom}
.tg .tg-j6zm{font-weight:bold;text-align:left;vertical-align:bottom}
.tg .tg-7zrl{text-align:left;vertical-align:bottom; white-space:nowrap;}
.tg .tg-rtra{background-color:#ED7D31;text-align:center;vertical-align:bottom}
@media screen and (max-width: 767px) {.tg {width: auto !important;}.tg col {width: auto !important;}.tg-wrap {overflow-x: auto;-webkit-overflow-scrolling: touch;}}</style>
<div class="tg-wrap"><table class="tg">
<thead>
  <tr>
    <th class="tg-j6zm"></th>
    <th class="tg-bobw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:black">Share via Zoom</span></th>
    <th class="tg-bobw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:black">VS Code Live Share</span></th>
    <th class="tg-bobw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:black">Virtual desktops</span></th>
    <th class="tg-bobw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:black">Cloud IDEs (Gitpod)</span></th>
    <th class="tg-bobw"><span style="font-weight:700;font-style:normal;text-decoration:none;color:black">Flexpair</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-7zrl"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black">Appear on screen</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
    <td class="tg-31j1"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#FFC000">No</span></td>
    <td class="tg-31j1"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#FFC000">No</span></td>
    <td class="tg-31j1"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#FFC000">No</span></td>
    <td class="tg-31j1"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#FFC000">No</span></td>
  </tr>
  <tr>
    <td class="tg-7zrl"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black">Hear each other</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">No</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">No</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
  </tr>
  <tr>
    <td class="tg-7zrl"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black">Share the mouse</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">No</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">No</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">No</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
  </tr>
  <tr>
    <td class="tg-7zrl"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black">Pair programming</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">No</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
  </tr>
  <tr>
    <td class="tg-7zrl"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black">Play music together</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">No</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">No</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">No</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">No</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
  </tr>
  <tr>
    <td class="tg-7zrl"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black">Team email inbox</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">No</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">No</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">No</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">No</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
  </tr>
  <tr>
    <td class="tg-7zrl"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black">Asynchronous access</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">No</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">No</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
  </tr>
  <tr>
    <td class="tg-7zrl"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black">Zero local installation</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">No</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">No</span></td>
    <td class="tg-31j1"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#FFC000">Depends</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
  </tr>
  <tr>
    <td class="tg-7zrl"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black">Git controlled config</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">No</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">No</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">No</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
  </tr>
  <tr>
    <td class="tg-7zrl"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black">Re-deploy in minutes</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">No</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">No</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">No</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
  </tr>
  <tr>
    <td class="tg-7zrl"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black">Persistent workspace</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">No</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
  </tr>
  <tr>
    <td class="tg-7zrl"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black">Requires fast upload</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">Yes</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">No</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">No</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">No</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">No</span></td>
  </tr>
  <tr>
    <td class="tg-7zrl"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black">Combine multi-cloud</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">Not applicable</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">Not applicable</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">No</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">No</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
  </tr>
  <tr>
    <td class="tg-7zrl"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black">Usable beyond coding</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">No</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
    <td class="tg-rtra"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#ED7D31">No</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
  </tr>
  <tr>
    <td class="tg-7zrl"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black">Windows environment</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">Yes</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">No</span></td>
    <td class="tg-18q7"><span style="font-weight:400;font-style:normal;text-decoration:none;color:black;background-color:#70AD47">No</span></td>
  </tr>
</tbody>
</table></div>

### Truly interactive wherever you are
- we do not waste valuable bandwidth for stuttering video
- we focus on live co-editing and pleasant, high quality audio
- easy 1-click switching between multiple shared desktops in your team
- minimize signal latency by a strategic choice of your server location
- includes a self-hosted team inbox for asynchronous collaboration by mail

<!-- Bei dieser Folie sollte die Grafik bzw. die Tabelle deutlich machen, wie die Funktionen eurer Lösung dazu beitragen, dass ihr euch von euren Mitbewerber*innen in wesentlichen Punkten unterscheidet. Das Analysieren und Anerkennen eurer Konkurrenz ist wichtig. Es zeigt, wie informiert ihr über euer Geschäftsfeld seid und wie kompetitiv euer Markt einzuschätzen ist.
 -->

## The Magic Sauce

- Infrastructure-as-code controlled from Terraform Cloud and GitHub
- flexibly scale the number of desktops and their compute power up and down
- desktops connect to a central communication hub via secure SSH tunnels
- combine (even free tier) resources from all major cloud providers


<!-- Was macht euch und euer Geschäft einzigartig? Bis hierhin sollte es einfach zu verstehen sein, was eure Stärken sind und welche Vorteile ihr bieten könnt. Welche Technologien oder Innovationen setzt ihr ein, die euer Startup einzigartig machen? -->

## Go-To-Market Strategy

### Carbon dioxide and waste reduction
- we go beyond the obvious "less business travel" argument
- no need for a second or third notebook, because Flexpair fully runs in your favorite browser
- Not so fun fact: Did you know that the production of a notebook until you switch it on the first time produces as much CO2 as driving about 1200 km with your car?
- Ubuntu 20.04 LTS with lightweight LXQt desktop requires only 1 GB of RAM (often available for free)

### Inclusion through maximum flexibility
- looks and sexual identity does not matter on Flexpair ⚧️🦄
- let anxiety related to being in front of a camera or among people not stop you 🎗️🧘 
- care for your child and about your career 👶🌡️
- source your top talent worldwide 🌍🧑🏿‍💻

### Personal boundaries and data protection
- Flexpair deliberately does not offer video conferencing. Because remote work should not feel like being a lone wolf in one moment and like Big Brother in the next.
- if you really need to give someone remote access to your local machine, please consider using [TeamViewer](https://www.teamviewer.com/en/) or comparable established solutions.
- full control over which data are stored and where
- a TLS certificate is automatically created and renewed for you

<!-- Hauptaugenmerk dieser Folie ist die Präsentation von Strategien zur Markteinführung. Es handelt sich hierbei um eure Pläne und Ideen, wie ihr euer Produkt oder eure Dienstleistung am besten auf den Markt bringt. Je konkreter und realistischer desto besser – orientiert euch dabei sowohl an eurem Budget als auch an euren Wettbewerbern. -->

## Our Team

With over 8 years of [data science experience](https://de.linkedin.com/in/fielenbach) under our belts, we understand that the success of these projects hinges on efficiently sharing work packages between coworkers before jointly delivering them to the client.

<!-- ### User experience
- Papa um uns Unterlagen für Wipperfliess zu zeigen
- Lea für Stationsversammlung
- Samy Amara
- Werner Merkl => Qt-Grafik
- Selbsthilfebüro für Karaoke-Abend
- Olga Heismann => Agile Coach
- Elisabeth Hirtl => Coworking
- Achim bei der Bahn für Mob Programming
- Cornelia May => Projekt Management
- Claudia Peters
- Natascha Rausch => Juristin
- [Stephan Teiwes](https://www.xing.com/profile/Stephan_Teiwes/cv) => Blogging
- Philipp Nowak und Tonia Nikolova => Mindfulness
- Hans Christian Hochkeppel (Sohn von Jürgen) => Design
- Mathias Rodenstein => Coach

### Technical review
- [Ying Gu](mailto:connygy@gmail.com) zum Demonstrieren Ihrer eigenen App
- [Lukas Camenzind](mailto:me@looke.ch) => IT Security
- [Stefan Lörwald](mailto:stefan.loerwald@gmail.com) => Software-Architektur
- [Christian Hallqvist](mailto:hall@id.ethz.ch) => IT Security
- [Björn Bastian](mailto:bjoernbastian@posteo.de) für CdE-Orga, freie Software
- [Oliver Kalz](https://www.xing.com/profile/Oliver_Kalz/cv) => IT Consulting
- Adrian Ngo => Webentwicklung
- Christophe Serra => IT Security
- [Christian Theel](https://www.linkedin.com/in/the-quantonomic/) => Online-Marketing
- Philipp Wollermann => Google
- [Peter Ziegenhein](mailto:peter.ziegenhein@gmail.com) => High Performance Computing
- [Ana Batanero](https://www.linkedin.com/in/ana-batanero-akerman-56825057/?midToken=AQFlMHtgh8kq9A&trk=eml-email_accept_invite_single_01-hero-2-prof%7Ecta&trkEmail=eml-email_accept_invite_single_01-hero-2-prof%7Ecta-null-6urekz%7Ej59q0f46%7Ez1-null-neptune%2Fprofile%7Evanity%2Eview) => Data Science
- [Thomas Locher](https://www.linkedin.com/in/thomas-locher-b68848102/) => Lead Consultant DevOps at Credit Suisse
- [Benjamin Knecht](mailto:knecht.ben@gmail.com) => Magic Leap
- Jannik Strötgen => Bosch
- Urs Burkhard

### Sales
- Jörg Gerigk => Mentor, excubo AG
- Ralf Anders => Market Intelligence
- [Miriam Godau](https://www.linkedin.com/in/miriamgodau/) => Founder of 42medien
- [Holger Greif](https://www.linkedin.com/in/holgergreif/) =>  COO at swissQuant
- Jürgen Hess
- Sebastian Knecht => Print und Digitalmedien
- Thomas Koch => IT Security and Sales
- Christian Kukuk
- Olaf Lahrsen
- Björn Münstermann
- Ali Özkan
- Henning Rusche
- Dr. Jürgen Schatz
- Dr. Thilo Simon => Fresenius Netcare
- Dr. Peter Strobel
- Georg Weissmüller => SAP
- Michael Fielenbach und Politik
- Prabhash Chaudhary => BlackRock
- Flurin Capaul => Hatte mal bei PwC präsentiert eine ähnliche Lösung
- Chiara Vedaldi => Novartis, Haben zusammen bei PwC Consulting I gemacht
- Ritesh Ramesh => CTO
- Christina Cappenberg => Dezernat für Bildung
- Riva-Melissa Tez => Intel
- Gianfranco Mautone => PwC Schweiz
- Reiko Mito => Investment Banking
- Kaisa Karvonen


Die Team-Folie ist für uns essenziell. Wir wollen sehen, wen wir womöglich in die CyberLab Community aufnehmen. Diese Folie zeigt die Gründer*innen und die Schlüsselpersonen, die euer Startup voranbringen sollen. Hier ist es wichtig zu zeigen, welche Aufgabenbereiche ihr in eurem Unternehmen habt und dass ihr ein komplementär aufgestelltes Team seid. Wir möchten also kurz und bündig sehen, welche Personen sich zusammengefunden haben, um das Startup zu langfristigen Erfolg zu bringen. -->

## Traction / Milestones / Roadmap

### Cloud-init support and 12 months free tier

#### Oracle Cloud Infrastructure (already adopted)
- 2% global market share, 19 cities
- [Fixed startup discount](https://www.oracle.com/de/startup/) of 500 USD
- `oci_core_instance` ([Official API](https://registry.terraform.io/providers/hashicorp/oci/latest/docs/resources/core_instance))

#### Amazon EC2 (already adopted)
- 33% global market share, 21 cities
- [Fixed startup discount](https://aws.amazon.com/de/activate/founders/) of 1350 USD
- `aws_instance` ([Official API](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/instance))

#### Microsoft Azure
- 18% global market share, 52 cities
- Only B2B startups can receive credits beyond the free account
- `azurerm_linux_virtual_machne` ([Official API](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/linux_virtual_machine))
- Public IP address attribute: `public_ip_address`

#### Alibaba Cloud
- 6% global market share, 22 cities
- [Startups can apply for](https://www.alibabacloud.com/de/startup/join-us) up to 10k USD
- `alicloud_instance` ([Verified API](https://registry.terraform.io/providers/aliyun/alicloud/latest/docs/resources/instance))
- Public IP address attribute: `public_ip`

### Cloud-init support and 1 month free tier

#### IBM Cloud
- 5% global market share, 8 cities
- [Startups can apply for](https://developer.ibm.com/startups/) up to 12k USD
- `ibm_compute_vm_instance` ([Community API](https://registry.terraform.io/providers/IBM-Cloud/ibm/latest/docs/resources/compute_vm_instance))
- Public IP address attribute: `ipv4_address`

#### OVH Cloud
- 11 cities
- [Startups can apply for](https://startup.ovhcloud.com/en/starters/) up to 10k EUR
- `openstack_compute_instance_v2` ([Verified API](https://registry.terraform.io/providers/terraform-provider-openstack/openstack/latest/docs/resources/compute_instance_v2))
- Public IP address attribute: `access_ip_v4`

#### Digital Ocean
- 11 cities
- Only approved accelerators
- `digitalocean_droplet` ([Verified API](https://registry.terraform.io/providers/digitalocean/digitalocean/latest/docs/resources/droplet))
- Public IP address attribute: `ipv4_address`

#### OpenTelekomCloud
- 2 cities
- [Startups can apply for](https://telekomhilft.telekom.de/t5/TechBoost/ct-p/techboost) 15k EUR
- `opentelekomcloud_compute_instance_v2` ([Community API](https://registry.terraform.io/providers/opentelekomcloud/opentelekomcloud/latest/docs/resources/compute_instance_v2))
- Public IP address attribute: `access_ip_v4`

#### Yandex.Cloud
- 3 cities
- [Startups can apply for](https://cloud.yandex.com/cloud-boost) up to 12k USD
- `yandex_compute_instance` ([Community API](https://registry.terraform.io/providers/yandex-cloud/yandex/latest/docs/resources/compute_instance))
- Public IP address attribute: `network_interface.0.nat_ip_address`

### Cloud-init support but no free tier with sufficient RAM allowance

#### Google Compute Engine
- 9% global market share, 3 cities
- Only approved accelerators
- `google_compute_instance` ([Official API](https://registry.terraform.io/providers/hashicorp/google/latest/docs/resources/compute_instance))
- Public IP address attribute: `network_interface.0.access_config.0.nat_ip`

#### TencentCloud
- 2% global market share, 15 cities
- No startup program
- `tencentcloud_instance` ([Verified API](https://registry.terraform.io/providers/tencentcloudstack/tencentcloud/latest/docs/resources/instance))
- Public IP address attribute: `public_ip`

### Record and replay handover sessions

We also believe that the best way of motivating is to track the impact of individual contributions and to provide a fair equity stake in eventual successes.

- voices as well as sound played on the desktop can be recorded as separate audio tracks
- no need to take notes, fully concentrate on asking the right questions
- participants can decide afterwards to keep or delete their individual tracks
- large video recordings are saved directly in the cloud, instead of cluttering your local disk

<!-- Solch eine Folie am Ende des Pitch Decks erzeugt Glaubwürdigkeit. Hier solltet ihr zeigen was ihr bis zum Status Quo alles erreicht und unternommen habt, um eure Idee zu validieren. Genauso interessant ist es auch zu wissen, was eure nächsten Schritte sind bzw. sein könnten. Solltet ihr bis dato schon Erfolge oder relevante Zahlen, wie Umsatz, Anzahl Kunden und/oder Nutzer, etc. generiert haben: platziert sie präsent auf dieser Folie. -->

## Call-To-Action

<!-- Leider wird diese Folie oft vergessen. Egal ob ihr euch für das CyberLab bewerbt oder euer Startup vor Investoren oder anderen Wettbewerben vorstellt: Jeder möchte wissen, was ihr mit der Präsentation bezwecken wollt. Warum seid ihr hier? Was wollt ihr erreichen? Und für uns am wichtigsten zu wissen: Warum wollt ihr ins CyberLab? -->


