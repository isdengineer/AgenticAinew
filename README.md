# AgenticAinew

docker run -d -v ollama:/root/.ollama -p 11434:11434 --name ollama ollama/ollama


docker exec -it ollama ollama pull llama3


docker exec -it ollama ollama pull mistral

docker exec -it ollama ollama pull nomic-embed-text

docker exec -it ollama ollama list


