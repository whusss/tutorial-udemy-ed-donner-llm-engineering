# Additional requirements

## Week 1

For `week1/community-contributions/01_webpage_summarizer.ipynb` I needed to install additional libraries for the Selenium Chrome web driver to work:

```bash
docker exec -it -u 0 tutorial-llm-engineering-1.0.4 /bin/bash
apt update
apt install -y libglib2.0-0 libnss3 libfontconfig1
```
