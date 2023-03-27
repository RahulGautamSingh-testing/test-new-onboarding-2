Tests 
1. Creates a PR for configureRenovate
2. When onboardingPr is merged creates update-pr
3. No packageFiles found
4. Modified PR title (no effect we didn’t update  the title)
5. Behind base works fine (since we merge now,  its not rebased just the pr-body is updated)
6. Conflicted -> adds comment
7. Modified -> merges and updates preview if there are changes
8. Add renovate.json myself when onboardingPr still open 
  - auto closes onboardingPr
  - if onboardingPr is modified adds abandoned to prTitle and leaves it open 
