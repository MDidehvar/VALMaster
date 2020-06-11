[Split](https://github.com/MDidehvar/VALMaster/split)

<html>
  <body>
    <script>
      (async () => {
        const response = await fetch('https://api.github.com/repos/:MDidehvar/:VALMaster/contents/');
        const data = await response.json();
        let htmlString = '<ul>';
        for (let file of data) {
          htmlString += `<li><a href="${file.path}">${file.name}</a></li>`;
        }
        htmlString += '</ul>';
        document.getElementsByTagName('body')[0].innerHTML = htmlString;
      })()
    </script>
  <body>
</html>

## MAP - BIND
### A Push
![image](https://user-images.githubusercontent.com/7889154/84332429-d3764e00-ab84-11ea-8c63-f245596ecd9c.png)

### B Push

### 
