```yaml
name: Gim Guhyun's github

on:
  event:
    - born: 2008-05-02
    - current-school: Gyeongbuk Software High School

jobs:
  build:
    runs-on: ubuntu-latest 

    steps:
    - name: Checkout Identity
      run: echo "Name: Gim Guhyun 👋"

    - name: Tech stack
      run: |
        echo "Javascript"
        echo "Typescript"
        echo "express.js"
        echo "AWS"
        echo "Kubernetes"

    - name: 🏆 Awards Received
      run: |
        echo "2023 Hacking Mail Idea Contest: 2nd Place"
        echo "cloud computing regional skills competition 3rd Place" 
        echo "4th GBSW Hackerton: Excellence Award"

    - name: Contact Info
      run: |
        echo "Email: gimguhyun0502@gmail.com"
```
