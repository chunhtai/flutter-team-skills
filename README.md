# Flutter Team Skills

This repository aggregates various skills and tools related to Flutter development and triage as submodules.

## Included Submodules

The following submodules are tracked in this repository using the owner-repo naming convention:

*   **chunhtai-skills**: [Source](https://github.com/chunhtai/skills)
*   **justinmc-flutter-skills**: [Source](https://github.com/justinmc/flutter-skills)
*   **loic-sharma-flutter_triage_tools**: [Source](https://github.com/loic-sharma/flutter_triage_tools)
*   **dkwingsmt-flutter-skills**: [Source](https://github.com/dkwingsmt/flutter-skills)
*   **piinks-flutter-skills**: [Source](https://github.com/Piinks/flutter-skills)

## Working with Submodules

### Cloning with submodules
To clone this repository along with all submodules:

```bash
git clone --recurse-submodules <repository_url>
```

### Updating submodules manually
To update all submodules to the latest commits on their tracked branches:

```bash
git submodule update --remote --recursive
```

## Automatic Updates

This repository includes a GitHub Action workflow to automatically update all submodules daily. 

*   **Schedule:** Runs daily at midnight UTC.
*   **Mechanism:** Checks for updates, updates pointers, and pushes changes directly to the repository if any updates are found.
*   **Workflow file:** `.github/workflows/update_submodules.yml`
