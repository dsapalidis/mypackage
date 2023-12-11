# Changelog

## v2.4.1 - 2023-11-15

This patch release comes with an improved set of Docker images and a few fixes to provide compatibility with recent versions of `pymatgen`.

### Docker
- Improved Docker images [[fec4e3bc4]](https://github.com/aiidateam/aiida-core/commit/fec4e3bc4dffd7d15b63e7ef0f306a8034ca3816)
- Add folders that automatically run scripts before/after daemon start in Docker image [[fe4bc1d3d]](https://github.com/aiidateam/aiida-core/commit/fe4bc1d3d380686094021515baf31babf47388ac)
- Pass environment variable to `aiida-prepare` script in Docker image [[ea47668ea]](https://github.com/aiidateam/aiida-core/commit/ea47668ea9b38581fbe1b6c72e133824043a8d38)
- Update the `.devcontainer` to use the new docker stack [[413a0db65]](https://github.com/aiidateam/aiida-core/commit/413a0db65cb31156e6e794dac4f8d36e74b0b2cb)

### Dependencies
- Add compatibility for `pymatgen>=v2023.9.2` [[1f6027f06]](https://github.com/aiidateam/aiida-core/commit/1f6027f062a9eca5d8006741df91545d8ec01ed3)

### Devops
- Tests: Make `PsqlDosStorage` profile unload test more robust [[f392459bd]](https://github.com/aiidateam/aiida-core/commit/f392459bd417bec8a3ce184ee8f753649bcb77b8)
- Tests: Fix `StructureData` test breaking for recent `pymatgen` versions [[093037d48]](https://github.com/aiidateam/aiida-core/commit/093037d48a2d92cbb6f068c1111fe1564a4500c0)
- Trigger Docker image build when pushing to `support/*` branch [[5cf3d1d75]](https://github.com/aiidateam/aiida-core/commit/5cf3d1d75e8d22d6a3f0909c84aa63cc228bcf4b)
- Use `aiida-core-base` image from `ghcr.io` [[0e5b1c747]](https://github.com/aiidateam/aiida-core/commit/0e5b1c7473030dd5b5027ea4eb0a658db9174091)
- Loosen trigger conditions for Docker build CI workflow [[22e8a8069]](https://github.com/aiidateam/aiida-core/commit/22e8a80690747b792b70f96a0e332906f0e65e97)
- Follow-up docker build runner macOS-ARM64 [[1bd9bf03d]](https://github.com/aiidateam/aiida-core/commit/1bd9bf03d19dda4c462728fb87cf4712b74c5f39)
- Upload artifact by PR from forks for docker workflow [[afc2dad8a]](https://github.com/aiidateam/aiida-core/commit/afc2dad8a68e280f01e89fcb5b13e7a60c2fd072)
- Update the image name for docker image [[17507b410]](https://github.com/aiidateam/aiida-core/commit/17507b4108b5dd1cd6e074b08e0bc2535bf0a164)