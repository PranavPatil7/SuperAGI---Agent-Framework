<p align="center">
  <a href="https://superagi.com//#gh-light-mode-only">
    <img src="https://superagi.com/wp-content/uploads/2023/05/Logo-dark.svg" width="318px" alt="SuperAGI logo" />
  </a>
  <a href="https://superagi.com//#gh-dark-mode-only">
    <img src="https://superagi.com/wp-content/uploads/2023/05/Logo-light.svg" width="318px" alt="SuperAGI logo" />
  </a>

</p>

<p align="center"><i>Open-source framework to build, manage and run useful Autonomous AI Agents</i></p>
    




### 💡 Features

- <b>Provision, Spawn & Deploy Autonomous AI Agents</b> - Create production-ready & scalable autonomous agents.
- <b>Extend Agent Capabilities with Toolkits</b> - Add Toolkits from our marketplace to your agent workflows.
- <b>Graphical User Interface</b> - Access your agents through a graphical user interface.
- <b>Action Console</b> - Interact with agents by giving them input and permissions.
- <b>Multiple Vector DBs</b> - Connect to multiple Vector DBs to enhance your agent’s performance.
- <b>Performance Telemetry</b> - Get insights into your agent’s performance and optimize accordingly.
- <b>Optimized Token Usage</b> - Control token usage to manage costs effectively.
- <b>Agent Memory Storage</b> - Enable your agents to learn and adapt by storing their memory.
- <b>Models</b> - Custom fine tuned models for business specific usecases.
- <b>Workflows</b> - Automate tasks with ease using ReAct LLM's predefined steps.

### 🛠 Toolkits
Toolkits allow SuperAGI Agents to interact with external systems and third-party plugins.

<a href="https://marketplace.superagi.com/" target="_blank"><img src=https://superagi.com/wp-content/uploads/2023/08/Twitter.png height=50px width=50px alt="Twitter" valign="middle" title="Twitter"></a> <a href="https://marketplace.superagi.com/" target="_blank"><img src=https://superagi.com/wp-content/uploads/2023/08/Coding.png height=50px width=50px alt="Coding Tool" valign="middle" title="Coding Tool"></a> <a href="https://marketplace.superagi.com/" target="_blank"><img src=https://superagi.com/wp-content/uploads/2023/08/Insta.png height=50px width=50px alt="Instagram" valign="middle" title="Instagram"></a> <a href="https://marketplace.superagi.com/" target="_blank"><img src=https://superagi.com/wp-content/uploads/2023/08/Knowledge_tool.png height=50px width=50px alt="Knowledge Search" valign="middle" title="Knowledge Search"></a> <a href="https://marketplace.superagi.com/" target="_blank"><img src=https://superagi.com/wp-content/uploads/2023/05/Group-113612.png height=50px width=50px alt="Email"  valign="middle" title="Email"></a> <a href="https://marketplace.superagi.com/" target="_blank"><img src=https://superagi.com/wp-content/uploads/2023/05/Group-113610.png height=50px width=50px alt="Jira" valign="middle" title="Jira"></a> <a href="https://marketplace.superagi.com/" target="_blank"><img src=https://superagi.com/wp-content/uploads/2023/05/Group-113611.png height=50px width=50px alt="File Manager" valign="middle" title="File Manager"></a> <a href="https://marketplace.superagi.com/" target="_blank"><img src=https://superagi.com/wp-content/uploads/2023/05/Group-113613.png height=50px width=50px alt="Google Search" valign="middle" title="Google Search"></a> <a href="https://marketplace.superagi.com/" target="_blank"><img src=https://superagi.com/wp-content/uploads/2023/05/Group-113615.png height=50px width=50px alt="Dall-E" valign="middle" title="Dall-E"></a> <a href="https://marketplace.superagi.com/" target="_blank"><img src=https://superagi.com/wp-content/uploads/2023/05/Group-113614.png height=50px width=50px alt="Github" valign="middle" title="Github"></a> <a href="https://marketplace.superagi.com/" target="_blank"><img src=https://superagi.com/wp-content/uploads/2023/05/Group-113616.png height=50px width=50px alt="Web Interaction" valign="middle" title="Web Interaction"></a> <a href="https://marketplace.superagi.com/" target="_blank"><img src=https://superagi.com/wp-content/uploads/2023/05/Group-113622.png height=50px width=50px alt="Duckduckgo" valign="middle" title="Duckduckgo"></a> <a href="https://marketplace.superagi.com/" target="_blank"><img src=https://superagi.com/wp-content/uploads/2023/08/Calendar_tool.png height=50px width=50px alt="Google Calendar" valign="middle" title="Google Calendar"></a> <a href="https://marketplace.superagi.com/" target="_blank"><img src=https://superagi.com/wp-content/uploads/2023/08/Search_tool.png height=50px width=50px alt="Google Calendar" valign="middle" title="Google Search"></a> <a href="https://marketplace.superagi.com/" target="_blank"><img src=https://superagi.com/wp-content/uploads/2023/08/Serp.png height=50px width=50px alt="Serp API" valign="middle" title="Serp API"></a> <a href="https://marketplace.superagi.com/" target="_blank"><img src=https://superagi.com/wp-content/uploads/2023/08/Searx.png height=50px width=50px alt="Searx" valign="middle" title="Searx "></a> <a href="https://marketplace.superagi.com/" target="_blank"><img src=https://superagi.com/wp-content/uploads/2023/08/Web_scraper_logo.png height=50px width=50px alt="Web Scraper" valign="middle" title="Web Scraper"></a> <a href="https://marketplace.superagi.com/" target="_blank"><img src=https://superagi.com/wp-content/uploads/2023/08/Notion_logo.png height=50px width=50px alt="Notion" valign="middle" title="Notion"></a> <a href="https://marketplace.superagi.com/" target="_blank"><img src=https://superagi.com/wp-content/uploads/2023/08/Apollo_logo.png height=50px width=50px alt="Apollo" valign="middle" title="Apollo"></a>

### ⚙️ Installation

You can install superAGI using one of the following three approaches.

#### ☁️ SuperAGI cloud

To quickly start experimenting with agents without the hassle of setting up the system, try [Superagi Cloud](https://app.superagi.com/)

1. Visit [Superagi Cloud](https://app.superagi.com/) and log in using your github account.

2. In your account settings, go to "Model Providers" and add your API key.

You're all set! Start running your agents effortlessly.

#### 🖥️ Local

1. Open your terminal and clone the SuperAGI repository.
```
git clone https://github.com/TransformerOptimus/SuperAGI.git 
```

2. Navigate to the cloned repository directory using the command:
```
cd SuperAGI
```
3. Create a copy of config_template.yaml, and name it config.yaml.

4. Ensure that Docker is installed on your system. You can download and install it from [here](https://docs.docker.com/get-docker/).

5. Once you have Docker Desktop running, run the following command in the SuperAGI directory:

   a. For regular usage:
      ```
      docker compose -f docker-compose.yaml up --build
      ```

   b. If you want to use SuperAGI with Local LLMs and have GPU, run the following command:
      ```
      docker compose -f docker-compose-gpu.yml up --build
      ```


6. Open your web browser and navigate to http://localhost:3000 to access SuperAGI.

#### 🌀 Digital Ocean

<p align="left">
<a href="https://cloud.digitalocean.com/apps/new?repo=https://github.com/TransformerOptimus/SuperAGI/tree/main"> <img src="https://www.deploytodo.com/do-btn-blue.svg"></a><br>Deploy SuperAGI to DigitalOcean with one click.
</p>

<a id="architecture">

### 🌐 Architecture
</a>
<details>
<summary>SuperAGI Architecture</summary>

![SuperAGI Architecture](https://superagi.com/wp-content/uploads/2023/09/SuperAGI-Architecture.png)
</details>

<details>
<summary>Agent Architecture</summary>

![Agent Architecture](https://superagi.com/wp-content/uploads/2023/06/Agent-Architecture.png)
</details>

<details>
<summary>Agent Workflow Architecture</summary>

![Agent Workflow Architecture](https://superagi.com/wp-content/uploads/2023/09/Workflow-Architecture.png)
</details>

<details>
<summary>Tools Architecture</summary>

![Tools Architecture](https://superagi.com/wp-content/uploads/2023/09/Tools-Architecture.png)
</details>

<details>
<summary>ER Diagram</summary>

![ER Diagram](https://superagi.com/wp-content/uploads/2023/09/ER-Diagram.png)
</details>

