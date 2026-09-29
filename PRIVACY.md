# Privacy Policy — Personal Ring Archive

Last updated: 29 September 2026.

## 1. Operator and scope

The operator is the individual who owns this documentation repository, the connected Oura account, and the private GitHub repository used for the project. The operator and the sole data subject are the same person.

Contact: **alexander.kochanov@gmail.com**.

This policy describes the personal setup documented in this repository. The project is not open for other people to connect their accounts.

## 2. Data used

The project retrieves the owner's records from the Oura API after the owner grants access. Depending on the selected permissions and export configuration, these records may include sleep, activity, readiness, heart rate, blood oxygen, workouts, tags, and sessions, together with associated dates and record identifiers. Profile information, email, or ring configuration is retrieved only if the corresponding access is granted and the export requires it.

The project also uses OAuth credentials and tokens to authenticate its requests. The owner signs in with Oura; the export script does not need or store the owner's Oura account password.

## 3. Purpose

Data is used for the owner's personal record keeping, organization, and analysis. The project does not sell the data, use it for advertising, publish it, or collect records from other individuals.

## 4. Processing and storage

Exports are processed by the owner's script and stored in the owner's private GitHub repository. Scheduled processing uses GitHub Actions. The owner may also keep local working copies on their own computer.

Oura supplies the source data, and GitHub provides repository hosting and automation infrastructure. Data therefore passes through these services; describing the repository as private does not mean that data remains solely on the owner's computer. Each provider's own terms and privacy practices also apply.

Repository access is controlled by the owner's GitHub settings and any permissions granted to integrations. The intended setup does not grant access to other individual users. The public documentation repository contains no health records or credentials.

## 5. Protection rules

The data repository must remain private. Credentials and tokens must be kept in GitHub Actions secrets or another protected credential store, separate from committed data files. Workflows must avoid printing tokens or health records in logs. The owner is responsible for reviewing repository and integration permissions and protecting their accounts.

These are operating requirements for the project, not a guarantee that every hosted service or device is free from security risk.

## 6. Retention, stopping access, and deletion

Records are retained only for the personal purpose described above and within any applicable provider restrictions. The owner reviews whether continued storage is needed and removes records that are no longer needed.

The owner can stop scheduled jobs and revoke the application's authorization through Oura. Revocation stops further authorized collection; it does not itself erase previously exported files.

To remove stored records, the owner must address the private repository, Git history, local copies, and any workflow logs or artifacts containing those records. Deleting a file in the latest commit alone leaves earlier versions in Git history. Provider-managed copies are governed by the provider's own retention procedures.

## 7. Public documentation and updates

These documentation pages contain no project-specific tracking code or data collection forms. GitHub's own website processing applies to visits to the pages.

The operator will update this policy if the data categories, purposes, storage, or access arrangements change.

## 8. Provider information

- [Oura privacy information](https://ouraring.com/privacy-policy)
- [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)

[Project overview](README.md) · [Terms of Service](TERMS.md)
