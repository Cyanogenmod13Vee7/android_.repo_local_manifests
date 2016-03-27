CM13 Manifests
========================

Project V1 / Project Vee3

Local manifests to build Android MarshMallow 6.0 to L1II and L3II

To initialize CM13 Repo:

    repo init -u git://github.com/CyanogenMod/android.git -b cm-13.0 -g all,-notdefault,-darwin

To initialize Repo's:

    curl --create-dirs -L -o .repo/local_manifests/local_manifest.xml -O -L https://raw.github.com/TeamVee/android_.repo_local_manifests/cm-13.0/local_manifest.xml

To sync:

    repo sync

To apply patchs:

    sh device/lge/vee-common/patches/apply.sh

To initialize the environment

    . build/envsetup.sh

To build for L1 II:

    brunch v1

To build for L3 II:

    brunch vee3