# CargoChain Project Roadmap

## Platform (Core)

### August version
- Review the authentication:
    - Decouple the authentication into a separate project, the Auth Provider. CargoChain won't
      be responsible to the authentication. The Auth Provider will be. CargoChain won't be able
      to access authentication data.
    - Will follow the OAuth 2.0 industry-standard protocol.

- Introduce organization
    - Accounts will be linked to an organization
    - Organizations can have sub-organizations
    - Administrators can create accounts
    - Tags are attached to organization
    - Profiles can be release to an organization (not necessarily to an account)

- Add the *Delayed* event

- Introduce Custom Schema for events. Organizations will be able to manage their own list of
  schema for events.

- Allow to set the visibility on events. [More details](https://github.com/jadelogistics/api-doc/wiki/API-Cargo-Events#visibility)

- Audit tracking: allow to retrieve the history of API calls for an account or organization.

- Rename *CargoProfileRefence* to *CcSecretId*

### Next
- Set propagation property on events.
[More details](https://github.com/jadelogistics/api-doc/wiki/API-Cargo-Events#propagation)

- Add new type of relation between 2 profiles: association. "Simple" link between two profiles.

## Apps
