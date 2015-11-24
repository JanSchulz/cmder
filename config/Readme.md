## Config

All config files must be in this folder. If there is no option to set this folder 
directly, it has to be hardlinked.

* `aliases`: aliases in cmd; called form vendor\init.bat; autocreated from 
  `vendor\aliases.example`.
* `*.lua`: clink completitions and prompt filters; called from vendor\cmder.lua after all 
  other prompt filter and clink completitons are initialized; add your own.
* `user_*.{sh|bat|ps1}: startup files for bash|cmd|powershell tasks; called from ther 
  respective startup scripts in `vendor\`; autocreated on first start of such a task
