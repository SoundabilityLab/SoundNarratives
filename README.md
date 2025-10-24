<div align="center" style="display: flex; justify-content: center; align-items: center; text-align: center;">
  <a href="https://github.com/binomial14/SoundNarratives" style="margin-right: 20px; text-decoration: none; display: flex; align-items: center;">
    <img src="system/frontend/public/soundnarratives.ico" alt="SoundNarratives" width="120">
  </a>
</div>

<div align="center" style="display: flex; justify-content: center; align-items: center; text-align: center;">
    <h2>
    SoundNarratives: Rich Auditory Scene Descriptions to Support Deaf and Hard of Hearing People
    </h2>
</div>

![Status](https://img.shields.io/badge/Version-alpha-brightgreen.svg)
![License](https://img.shields.io/badge/License-TBD-blue.svg)

Copyright © 2025 The Regents of the University of Michigan

## System

### Frontend

Start UI

```bash
npm install
HTTPS=true SSL_CRT_FILE=../cert.pem SSL_KEY_FILE=../key.pem PORT=2000 npm start
```

### Backend

Build python environment:

```bash
python -m venv s2t_env
source s2t_env/bin/activate
pip install -r backend/requirements.txt
```

Start backend

```bash
cd backend
python server.py
```


### Trouble shooting

- Use incognito mode with Google Chrome browser

## Codebook

The codebooks for the formative study and the user study.

## Support 

- Developed with [Dhruv Jain](https://web.eecs.umich.edu/~profdj/) and collaborators at [The Soundability Lab](https://soundability.eecs.umich.edu)
- Contact [Leo Wu](https://binomial14.github.io) @SoundabilityLab through email `lyuanwu` at umich.edu

