# 下载中心

<style>
@keyframes neon{0%{box-shadow:0 0 5px #0ff,0 0 10px #0ff,0 0 20px #0ff}50%{box-shadow:0 0 10px #0ff,0 0 20px #0ff,0 0 40px #0ff}100%{box-shadow:0 0 5px #0ff,0 0 10px #0ff,0 0 20px #0ff}}
.btn-dl{display:inline-flex;align-items:center;gap:8px;margin:12px 0;padding:14px 32px;font-size:18px;font-weight:700;color:#fff;background:linear-gradient(135deg,#00f5ff 0%,#0099ff 100%);border:none;border-radius:50px;text-decoration:none;animation:neon 2s infinite;transition:transform .3s}
.btn-dl:hover{transform:scale(1.05)}
.log-box{background:#0d1117;color:#c9d1d9;padding:16px;border-radius:8px;white-space:pre-wrap;font-family:Consolas,Monaco,"Courier New",monospace;max-height:300px;overflow-y:auto}
</style>

## 🚀 0.0.6 系列（推荐，Win10/11）

- **最新版本号**  
  <span id="v-006">加载中…</span>

- **更新日志**  
  <div class="log-box" id="log-006">加载中…</div>

- <a class="btn-dl" href="https://gitee.com/linfon18/minecraft-connect-tool-api/raw/master/006/Latest.exe">
    <svg width="20" height="20" fill="currentColor"><path d="M5 20h14v-2H5v2zm7-18L5.5 9.5 7 11l5-5v14h2V6l5 5 1.5-1.5L12 2z"/></svg>
    立即下载 0.0.6
  </a>

---

## 🔧 0.0.5 LTS（仅 Win7）

- **最新版本号**  
  <span id="v-005">加载中…</span>

- **更新日志**  
  <div class="log-box" id="log-005">加载中…</div>

- <a class="btn-dl" href="https://gitee.com/linfon18/minecraft-connect-tool-api/raw/master/005/Latest.exe">
    <svg width="20" height="20" fill="currentColor"><path d="M5 20h14v-2H5v2zm7-18L5.5 9.5 7 11l5-5v14h2V6l5 5 1.5-1.5L12 2z"/></svg>
    立即下载 0.0.5 LTS
  </a>

<!-- 浏览器端脚本：JSONP 拉取纯文本 -->
<script>
(function () {
  function loadText (url, id) {
    var cb = 'cb_' + Math.random().toString(36).slice(2)
    var script = document.createElement('script')
    script.src = url + '?callback=' + cb
    window[cb] = function (txt) {
      document.getElementById(id).textContent = txt.trim()
      delete window[cb]
      script.remove()
    }
    script.onerror = function () {
      document.getElementById(id).textContent = '获取失败，请稍后刷新重试。'
      script.remove()
    }
    document.head.appendChild(script)
  }

  loadText('https://gitee.com/linfon18/minecraft-connect-tool-api/raw/master/version006.txt',  'v-006')
  loadText('https://gitee.com/linfon18/minecraft-connect-tool-api/raw/master/updatelog6',      'log-006')
  loadText('https://gitee.com/linfon18/minecraft-connect-tool-api/raw/master/005/version005',  'v-005')
  loadText('https://gitee.com/linfon18/minecraft-connect-tool-api/raw/master/005/005Updatelog','log-005')
})()
</script>
