# ARcore
git clone -b 4.20-arcore \
https://github.com/google-ar-unreal/UnrealEngine.git
# Checkout your target branch, which must be based on Unreal 4.20
git checkout <target-branch>

# Add google-ar-unreal as a remote
git remote add google-ar-unreal https://github.com/google-ar-unreal/UnrealEngine.git

# Fetch and merge the arcore branch
git fetch google-ar-unreal 4.20-arcore
git merge google-ar-unreal/4.20-arcore
