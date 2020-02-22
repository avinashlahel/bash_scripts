#Find a directory and delete only that directory in that folder
find . -type d -name "node_modules" -maxdepth 1 -exec rm -rf {} +
