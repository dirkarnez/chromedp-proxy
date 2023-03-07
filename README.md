

### TODOs
- [ ] https://github.com/chromedp/chromedp/blob/2651bfb9cfa2b313455bb44953864b2b2119addf/allocate.go#L435
  - ```go
    login  := os.Getenv("PROXY_LOGIN")
    password := os.Getenv("PROXY_PASSWORD")
    proxy_addr := os.Getenv("PROXY_ADDR") //127.0.0.1:1080
    schema := os.Getenv("PROXY_TYPE") //socks5:// or http://
    chromedp.ProxyServer(fmt.Sprintf("%s%s:%s@%s", schema,login,password,proxy_addr))
    ```
