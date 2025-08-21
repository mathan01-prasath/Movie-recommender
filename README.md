# Movie recommender 

Simple movie recommender app you can submit on GitHub. It includes:
- Frontend: HTML, CSS, JavaScript (Fetch GET/POST)
- Backend: Node.js + Express
- Docker & Kubernetes (Minikube)
- Jenkins CI/CD + SonarQube (optional)
- Basic monitoring via /metrics (Prometheus)

## Run locally (easiest)
1) Install Docker Desktop.
2) In a terminal, go to this folder and run:
   ```bash
   docker compose up --build
   ``

## Upload to GitHub (no command line needed)
1) Download this project ZIP and unzip it.
2) Go to https://github.com → New → Repository → name it `Movie Recommender` → Create.
3) On your new repository page, click **Add file** → **Upload files**.
4) Drag-and-drop everything **inside** the unzipped folder (not the folder itself) into the page.
5) Scroll down and click **Commit changes**.
6) Your submit link is the repository URL, e.g.:
   `https://github.com/<your-username>/event-booking-portal`

## Notes
- To push images, edit `<REGISTRY>` in Kubernetes YAMLs and Jenkinsfile.
- You can ignore Jenkins/SonarQube if you only need a working demo.
