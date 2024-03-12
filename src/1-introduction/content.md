---
Title: "Installation"
---

To install the application, you must have Docker installed on your computer.

## Docker installation

1. Go to the [official Docker website](https://www.docker.com/get-started) and follow the instructions to download Docker for your operating system (Windows, macOS, or Linux).

2. After installing Docker, make sure that Docker is successfully running on your computer. You can verify this by executing the command:

```bash
docker --version
```

## Dowloading and running

Open the terminal (command prompt) on your computer. Clone the repository containing our `control` script by executing the following command:

```bash
git clone https://github.com/semantic-pie/control
```

Navigate to the directory of our application:
```bash
cd control
```

And run:

```bash
./control.sh run
```

Docker containers will be pulled from docker hub and services will start.
