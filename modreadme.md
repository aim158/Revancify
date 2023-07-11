```
curl -sL "https://raw.githubusercontent.com/aim158/Revancify/main/install.sh" | bash
```

<details>
  <summary>If the above one doesn't work, use this.</summary>

  ```
pkg update -y -o Dpkg::Options::="--force-confnew" && pkg install git -y && git clone --depth=1 https://github.com/aim158/Revancify.git && ./Revancify/revancify
```
