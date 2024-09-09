# 09-09-2024 demo

This is a demo to practice creating a local repo first then pusing to the remote.

`git log`: view the trace of the commits
`git remote add NAME URL`: adds the remote with that specific name to the local
`git restore`: restores to a specific instance in the past
    * `git restore HASH FILE` resotres a file to a specific instance specified by the hash

### `git log`

This shows the commit then a unique identifier for the commit. This unique identifier can be used to restore to a specific commit version. Ca use the first few characters of the string and they would be used to reverse.
**Under the hood**
It creates a snapshot of the files in that specific instance and adds it to the end of the current file we have. This makes it possible to revert back. 
