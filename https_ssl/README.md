```plaintext
https_ssl/
│
├── 0-world_wide_web
│   ├── README.md
│   ├── 0-world_wide_web.sh
│   └── ...
│
├── 1-haproxy_ssl_termination
│   ├── README.md
│   ├── 1-haproxy_ssl_termination.sh
│   └── haproxy.cfg
│
├── 2-redirect_http_to_https
│   ├── README.md
│   ├── 2-redirect_http_to_https.sh
│   └── haproxy.cfg
│
└── README.md
```

In this structure:

- The `https_ssl` directory contains subdirectories for each task.
- Each task subdirectory (`0-world_wide_web`, `1-haproxy_ssl_termination`, `2-redirect_http_to_https`) contains a `README.md` file describing the task, a Bash script (e.g., `0-world_wide_web.sh`, `1-haproxy_ssl_termination.sh`, `2-redirect_http_to_https.sh`) for implementing the task, and any necessary configuration files (e.g., `haproxy.cfg` for HAProxy configurations).
- The main `README.md` file in the root of the `https_ssl` directory can provide an overview of the tasks and instructions for running them.

Remember to include actual content, code, and configurations in the respective files and directories as per the task requirements.