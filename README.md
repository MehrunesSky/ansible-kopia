# Kopia ansible role

Ansible role for https://kopia.io/

Only supports GCS and GDRIVE.

## Role Variables

- `kopia_gcs_bucket`: GCS destination bucket for Kopia
- `kopia_gcs_email`: email for SA
- `kopia_gcs_password`: repos password
- `kopia_gdrive_folder_id`: Folder id for gdrive
- `kopia_gdrive_credential_file`: Path for credential file


## Example Playbook

```yaml
  - hosts: servers
    roles:
        - { role: ansible-kopia, kopia_gcs_bucket: "foo-1234" }
```

## License

MIT
