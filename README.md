# Process-Inject-shellcode

/* SIMPLE PROCESS INJECTION
---------------------------------
*/
----------------------------------
	Injects shellcode into an a newly spawned remote process.
key win32 API calls:
  - kernel32.dll:
    1: 'OpenProcess'
    2: 'VirtualAllocEx (PAGE_EXECUTE_READ_WRITE)'
    3: 'WriteProcessMemory'
    4: 'CreateRemoteThread'
    ----------------------------------
*/
