
## ✅ 

```bash
```

## telescope error cant search using <leader>sg ✅ 
instal ripgrep because it depends on it

## yank to clipboard ✅  
need to install system clipboard (xclip, exsel, etc), this also will fallback to tmux if it's on tmux (read `h: clipboard`)
```
vim.schedule(function()
  vim.opt.clipboard = 'unnamedplus'
end)
```


## non-inractive terminal (!) can't use aliases in ~/.bashrc❌
