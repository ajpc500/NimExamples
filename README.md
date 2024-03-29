# Nim Examples

This repo contains some example Nim projects.

| Name | Description |
| -------------|-------------------| 
| MessageBoxShellCodeInject | The original [code](https://github.com/byt3bl33d3r/OffensiveNim/blob/master/src/shellcode_bin.nim) we've adapted from @byt3bl33d3r's OffensiveNim repo |
| SysCallsMessageBoxShellCodeInject | An adapted version of `MessageBoxShellCodeInject` that makes use of Native API and inline assembly generated through [NimlineWhispers](https://github.com/ajpc500/NimlineWhispers) |
| SysCallsMessageBoxQueueUserAPCInject| An alternative injection example using syscalls to execute NtQueueUserAPC. This also includes the `blockdlls/ppid-spoof/acg` [example](https://github.com/byt3bl33d3r/OffensiveNim/blob/master/src/blockdlls_acg_ppid_spoof_bin.nim) from @byt3bl33d3r's repo to spawn the target process |

The `SysWhispers2` folder includes an identical instance of the `SysCallsMessageBoxShellCodeInject` example but has syscalls generated using [NimlineWhispers2](https://github.com/ajpc500/NimlineWhispers2).


The process to create Nim projects with inline assembly is described here: https://ajpc500.github.io/nim/Shellcode-Injection-using-Nim-and-Syscalls/
