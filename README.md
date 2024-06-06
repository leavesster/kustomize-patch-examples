# kustomize-patch-example


<h3 align="center"><br><a href="./README_zh.md">[简体中文]</a><br></h3>

This repository showcases the usage of kustomize's built-in [Patches](https://kubectl.docs.kubernetes.io/references/kustomize/kustomization/patches/) plugin.

Patches support two types of resource modifications: strategic merge (handled by the patchesStrategicMerge plugin) and json patch (handled by the patchesJson6902 plugin). Both of these plugins have been deprecated, with their logic and functionality now incorporated into the patches system.