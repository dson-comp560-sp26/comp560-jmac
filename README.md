# comp560-jmac

This repo contains John MacCormick's experiments for the COMP560 research project. 

## Setup

### Virtual Environment (Recommended)

Using a virtual environment is recommended to prevent dependency conflicts with other Python projects and ensure a reproducible setup. It follows Python best practices and makes it easier for newcomers to get started.

#### Creating and Activating a Virtual Environment

**For macOS/Linux:**
```bash
python3 -m venv venv
source venv/bin/activate
```

**For Windows:**
```bash
python -m venv venv
venv\Scripts\activate
```

#### Installing Dependencies

Once your virtual environment is activated, install the required dependencies:

```bash
pip install -r requirements.txt
```

#### Deactivating the Virtual Environment

When you're done working on the project, you can deactivate the virtual environment:

```bash
deactivate
```

## Notes

* One of the onboarding activities asks you to make a change to one of the files here and submit the change as a pull request.
* At the time of writing (December 18, 2025), this repo contains two experiment collections: `alphabet` and `tiny-shakespeare`. The `README.md` and `useful-commands.md` files in those directories contain suggestions of how to run the experiments in these collections. Please submit improvements to these instructions as PRs.


