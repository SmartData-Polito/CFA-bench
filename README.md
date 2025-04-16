# CFA-bench


## Installation
Ensure to have `tshark` installed on your machine. Otherwise run
```bash
apt-get install tshark
```
Create and activate a virtual environment
```bash
python3 -m venv .venv
source .venv/bin/activate
```
Install the library and the required packages
```bash
./setup.sh
```
Export the project folder path variable
```bash
echo "PROJECT=$(pwd)" > .env
```
and the OpenAI API key
```bash
echo "OPENAIKEY=PUT_YOUR_API_KEY_HERE" >> .env
```
