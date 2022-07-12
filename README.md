# PyScript use+ upload to Azure

![image](https://user-images.githubusercontent.com/7007970/178420667-a8d9d8b5-4dfd-4e95-bf1b-df95a4a87e9a.png)

1. Get all sources into VSCode
2. Live Server
    1. In VSCode add extension: Live Server
    2. In VSCode: Ctrl Shift P -> Open with live server
    3. In VSCode: check your code in Live Server. It shall be like in picture. If all works fine, move next
3. Deploy to Azure
    1. Go to Azure -> Storage Accounts -> Create
    2. In Azure: go to created Storage Account -> Data management -> Static website. Click Enable.
    3. In VSCode: install Azure Storage extension
    4. In VSCode: Click on project folder-> Deploy to Static Website via Azure Storage...
    5. In VSCode: sign to Azure. After sign process got page: 'You are signed in now and can close this page.'
    6. In VSCode: select resource, you created.
    7. Done
