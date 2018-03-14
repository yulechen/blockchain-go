`go get github.com/davecgh/go-spew/spew`
spew 可以帮助我们在 console 中直接查看 struct 和 slice 这两种数据结构。

`go get github.com/gorilla/mux`
Gorilla 的 mux 包非常流行， 我们用它来写 web handler。

`go get github.com/joho/godotenv`
godotenv 可以帮助我们读取项目根目录中的 .env 配置文件，这样我们就不用将 http port 之类的配置硬编码进代码中了。比如像这样：
ADDR=8080