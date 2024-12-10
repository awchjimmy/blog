# matplotlib 在 windows 底下出現 missing dll

### 快速解決辦法

```sh
pip install msvc-runtime
```

注意：就算專案使用 `venv`，也要在專案外面安裝 `msvc-runtime`，外面安裝完成後再回到 `venv` 即可執行。

出處：Stackoverflow
