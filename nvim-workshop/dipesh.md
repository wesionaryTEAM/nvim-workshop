# Try out (second part)

- try some vim motions
- check exercise-1 file of the slides repo. 

<br />

### Try Mode :)  

--- 

# Exercises

- Open `exercise-2.js` file and try to change the parameters on fizzbuzz. 

1. Try changing parameter of fizzbuzz program. 
2. Try changing `fiz` to `wesionary`
3. Try changing `buzz` to `team`

--- 

# Learning Materials

- Vim tutor

  in normal mode, type `:Tutor` and enter. Official vim tutorial.

- [Vim snake game](https://vimsnake.com/)

- [Vim Adventures](https://vim-adventures.com/) 


--- 

# Lua  

- https://www.lua.org/

- Extremely minimal programming language

- Used for configuring different applications

    https://en.wikipedia.org/wiki/List_of_applications_using_Lua

- Some snippet [LearnXinYminutes](https://learnxinyminutes.com/docs/lua/)

- A brief intro [Fireship](https://www.youtube.com/watch?v=jUuqBZwwkQw)


```lua
if a > 40 then 
    print("yoo")
end

function abc() 
    -- do something
end

```

--- 

# Plugin System 

- Personalized Development Environment (PDE)
- Coding IDE yourself 

- VimScript (old method) [Sample](https://gist.github.com/simonista/8703722)  , Lua (new one)
- vim configurations made using programming, extremely customizable


---

# Lazy Plugin Manager 

- folke/lazy.nvim (gaining popularity), wbthomason/packer.nvim

- Lazy load modules depending on different conditions 

  eg; new file loaded, new file created, file saved etc...

- [lazy.nvim](https://github.com/folke/lazy.nvim), (a lot of features) 


--- 

# Basic plugins

- Telescope (File Search, Finder)
- LSP Configuration Plugins 
- Conform (Autoformatting Plugin)
- nvim-cmp (Completion Plugin)
- Snippets engine (LuaSnip)
- Themes (tokyonight)
- Lualine
- Treesitter

🤯

---

# Comparing VSCode plugins with nvim

| vscode | nvim | 
| -- | -- |
| autocompletion | nvim-cmp | 
| snippets | lua snip | 
| debugger | nvim dap |
| code formatting | null ls | 
| file finding | Telescope | 
| Git | LazyGit, Fugitive | 

---

# To much configuration ... (configuration hell?)

- Preconfigured distributions (Full fledged IDE's using nvim) 
  - LazyVim, NvChad

- Super minimal configuration [kickstart.nvim](https://github.com/nvim-lua/kickstart.nvim)
- Statrting point for configuring and playing with nvim
- Youtube video from creator of kickstart. [here](https://www.youtube.com/watch?v=m8C0Cq9Uv9o)

---

# Question/Answers

- can nvim do this? my ide does it... 

---

# Developer Workflow

- tmux, fzf, nvim (my workflow) and walkthrough
