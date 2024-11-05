# Putting-AI-big-models-on-computers
Install Docker and Ollama in Releases（Please select the Releases that match your computer to download）, enter in the terminal:
docker run -d -p 3000:8080 --add-host=host.docker.internal:host-gateway -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:main
After waiting for the download to complete, you need to click the docker icon in the menu bar，click the "go to the Dashboard" button ，You will find a button called 3000:8080 in the "Port(s)" column. Click it to enter a web page. You can use ollama to download the AI ​​language model (the download method is available on the ollama official website https://ollama.com/library. Paste the command into the terminal and wait for the download). You can find the AI ​​model you downloaded in the web page you just opened. You can choose AI to talk to AI.
Note: Running AI will consume a lot of performance. You can exit docker and ollama when not in use.
