Ansible Galaxy role: `gbraad.dotfiles-devenv`
=============================================

Runs devenv from my dotfiles to start instant development environments


## Usage

```shell
$ ansible-galaxy role install gbraad.dotfiles-devenv
```

## Requirements


## Role Variables



## Dependencies


## Example Playbook

`site.yaml`
```yaml
- name: Run `ps ax` in dotfedora
  hosts: localhost
  roles:
    - role: gbraad.dotfiles-devenv
      vars:
        prefix: dotfedora
        command: exec
        args: ps ax
```

```shell
$ ansible-playbook site.yml 
```

An example exists at [`gbraad-dotfiles/ansible-dotfiles-example`](https://github.com/gbraad-dotfiles/ansible-dotfiles-example/).


## License

MIT


## Author Information

| [!["Gerard Braad"](http://gravatar.com/avatar/e466994eea3c2a1672564e45aca844d0.png?s=60)](http://gbraad.nl "Gerard Braad <me@gbraad.nl>") |
|---|
| [@gbraad](https://gbraad.nl/social) |
