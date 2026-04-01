<!--
	file: vscode.md
	author: luxurmist
	date: 2026-04-01
-->


# VSCode使用
Ctrl+Shift+P 命令面板

## 代码片段 snippets
命令面板输入 snippets

```json
{   
    "文件头注释 //格式": {
	    "prefix": "info//",
	    "body": [
		    "// filename: ${TM_FILENAME}",
		    "// author: luxurmist",
		    "// date: ${CURRENT_YEAR}-${CURRENT_MONTH}-${CURRENT_DATE}"
	    ]
    }
}

```
