---
title: Environments
cascade:
  type: docs
---

In Postman, an environment represents a collection of key-value pairs that store specific configuration values required for making API calls. These configuration values could be related to different aspects of your application, such as base URLs, authorization keys, or any variable needed while working with APIs. By defining environments, you can easily switch between different sets of configurations without modifying individual requests manually. This feature saves time and reduces errors when working with multiple applications or scenarios where varied configurations are essential.

Key features of Postman Environments include:

1. Environment Variables - Create and assign key-value pairs representing unique configurations. For example, `baseUrl` might have a value of `https://api.example.com`. You can reference these variables within requests, tests, and scripts.
2. Active Environment Selector - Choose from available environments listed at the top right corner of the main window. Switching the active environment will apply its corresponding variables across all open requests and collections.
3. Global Variables - Define global variables accessible throughout Postman, regardless of the currently activated environment. To create a global variable, add the desired key-value pair under "Manage Environments" > Globals tab.
4. Data Scripts - Use Pre-request Scripts and Tests sections to manipulate environment variables before sending requests and validate response content accordingly.
5. Import & Export - Share environments with others or transfer them between instances of Postman by importing and exporting files in JSON format.
6. Managing Multiple Configurations - Organize and maintain complex projects involving numerous configurations, ensuring consistent behavior across teams and systems.

Environments help streamline API development, testing, and collaboration processes by providing flexible ways to handle varying configurations and promoting reusability. They also facilitate better management of dynamic data and improve overall productivity.
