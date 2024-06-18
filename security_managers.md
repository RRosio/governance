## Security Manager Role

The following information outlines the role and responsibilities of the Security Manager within the Jupyter project. For detailed instructions and additional context, refer to the official [Github documentation](https://docs.github.com/en/organizations/managing-peoples-access-to-your-organization-with-roles/managing-security-managers-in-your-organization).

### Permissions
The security manager role grants the following permissions:
	- Read access on all repositories in the organization, in addition to any existing repository access.
	- Write access on all security alerts in the organization.
	- The ability to configure code security settings at the organization level.
	- The ability to configure code security settings at the repository level.
	- Note: Security managers cannot manage the security team members.

An organization owner can create and manage a `security-managers` team. See [how to create a Github team](https://docs.github.com/en/organizations/organizing-members-into-teams/creating-a-team).

### Recommended Members
The security manager role can be applied to selected members of the security-council team who may be required to audit security across various Jupyter subprojects.

As of the most recent update, the current members are:
	- Rick Wagner (@rpwagner)
	- Matthias Bussonnier (@Carreau)
	- Rosio Reyes (@RRosio)

### Purpose
The security manager role will give [members of the Jupyter Security council](https://github.com/jupyter/security/blob/main/README.md#jupyter-security-subproject-council) the permissions necessary to collaborate with Jupyter sub-project maintainers in evaluating, processing and handling security across Jupyter. This role may also promote a more uniform and united handling of security across the Jupyter ecosystem.  

### Accountability and Authority
Security managers act in the interest of the community, ensuring security across the Jupyter ecosystem. The role offers no additional authority over the project and is intended to facilitate working with project maintainers to promote security and security best practices.

### Maintaining Membership Accuracy
The Jupyter Security council will establish an auditing schedule to ensure that the security manager team members are consistent across organizations and reflect the most current membership status for all individuals of the security manager team. 

The selection of the members of the `security manager team` will be an agreed upon group of members from the Jupyter Security council selected via voting in a private Jupyter organization repository. The list of members will be shared with an organization owner and any necessary changes will be communicated. 

### Subproject Team Responsibilities and Collaboration
No additional responsibilities are taken on by the subproject team. The Jupyter Security council will establish an auditing schedule and communicate with teams and organization owners to ensure that the security manager roles across Jupyter organizations are up to date. This role should collaborate with Jupyter subproject maintainers to ensure the overall security across Jupyter subprojects.