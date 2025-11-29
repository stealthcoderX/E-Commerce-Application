The pipeline handles:

⚙️ Tool installation

🌱 Git checkout
🧱 Maven compile + test
🔍 SonarQube code quality scan
📦 Maven packaging
📤 Push artifacts to Nexus
🐳 Docker image build + security scan (Trivy)
📥 Push Docker image to registry
🚚 Deploy to Kubernetes cluster
🔁 Verify deployment

Everything passed successfully — the green boxes confirm all stages executed smoothly.
At the bottom, the SonarQube Quality Gate shows the application passed all quality checks, meaning the code is clean, secure, and ready for production.
<img width="1920" height="1080" alt="Screenshot (1029)" src="https://github.com/user-attachments/assets/f94cd3bc-41a6-4c60-bdfc-7fde24778bb0" />
<img width="1920" height="1080" alt="Screenshot (1021)" src="https://github.com/user-attachments/assets/e4a86016-6162-4663-9135-e813e45348c6" />
<img width="1920" height="1080" alt="Screenshot (1033)" src="https://github.com/user-attachments/assets/41ea2c28-8b26-4d50-9ead-066f2e20dc5c" />
