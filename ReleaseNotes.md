# Release notes

- Update crates for pallet 0.6.3


## pallet-crates-0.5.0


## pallet-crates-0.4.4


## pallet-crates-0.4.3

- Update for 0.5.0-SNAPSHOT
  Change pallet.resource.* to pallet.action.*. Change stevedore calls to
  script functions to use unquote and the pallet.script.lib namespace. 
  Change request to session.  Change build-resources to build-actions.


## pallet-crates-0.4.2


## pallet-crates-0.4.1


## pallet-crates-0.4.0


## pallet-crates-0.4.0-beta-1

- working node-list compute service

- Add retrieval of files from node. Refactor sending of files to remove
  *file-transfers*. Add ssh-key/record-public-key to retrieve a users
  public key from a remote node.

- Refactoring to a more functional implementation

- Made converge run phase by phase, instead of node by node.  Added
  pre-phase. Removed :reload-all from tests to avoid deftype problems.

- removed 1.1 compat.  fixed compile errors from id/providerId changes

- Added target/*all-nodes* and target/*target-nodes*.  Made target vars
  uninitialised. Tidied mock.

- unification of defresource & defcomponent, elimination of atom usage in
  general, formalized sub-phase / execution type

- clojure 1.1 / 1.2 compatibility modifications

- clojure 1.1 / 1.2 compatibility modifications

- Added defnode, lift and configuration phases. Adds declaritive
  configuration definiton.

- minor improvements, and doc fixes

- fixed bug from jclouds api change. added resources and crates

- cleanup of line endings and tests

- added package resource, tests, switched to clj-ssh, and more

