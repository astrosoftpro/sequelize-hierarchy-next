# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## 1.0.0 (2023-01-16)


### Bug Fixes

* `beforeCreate` hook work with `options.fields` ([118e9be](https://github.com/astrosoftpro/sequelize-hierarchy-next/commit/118e9be476985f42cb95c8aed1c07dbd4e5baed0))
* `primaryKey` option (closes [#67](https://github.com/astrosoftpro/sequelize-hierarchy-next/issues/67)) ([3184729](https://github.com/astrosoftpro/sequelize-hierarchy-next/commit/31847291c4daf1e0a2bdb434a97903063bb78b70))
* `rebuildHierarchy` support custom primary keys ([ff86955](https://github.com/astrosoftpro/sequelize-hierarchy-next/commit/ff869559906a355447b2b83fcddf1ae9903dbe1d))
* Allow `underscored: false` option on model to override global option ([ec134d7](https://github.com/astrosoftpro/sequelize-hierarchy-next/commit/ec134d70ba2c36a3ec3206c5ff6a261e70057f51))
* Bug introduced by removal of `Sequelize.Utils._` in Sequelize v4.11.0 (closes [#142](https://github.com/astrosoftpro/sequelize-hierarchy-next/issues/142)) ([3c99309](https://github.com/astrosoftpro/sequelize-hierarchy-next/commit/3c99309ebd610814decc8581d6f9d212cdea70a7))
* Clone `options.fields` before mutating it to prevent `options` object being mutated externally ([9536fb7](https://github.com/astrosoftpro/sequelize-hierarchy-next/commit/9536fb74492c7a57596ec212764d2c8014b9657b))
* Handle discarded includes if `attributes: []` ([f04e145](https://github.com/astrosoftpro/sequelize-hierarchy-next/commit/f04e145d2dc7d1b50230be67e5d924a1141cad46))
* labels option broken due to bad use of this ([17d003d](https://github.com/astrosoftpro/sequelize-hierarchy-next/commit/17d003df3faabd525f3f6adae7f95118e3c7f1ec))
* Semver version ranges for patches ([f0cb3ac](https://github.com/astrosoftpro/sequelize-hierarchy-next/commit/f0cb3ac208519ce0e2ed34e81775eb6739e0448f))
* Support model fields with different table field names (closes [#70](https://github.com/astrosoftpro/sequelize-hierarchy-next/issues/70)) ([86ff2ae](https://github.com/astrosoftpro/sequelize-hierarchy-next/commit/86ff2ae3b30a04b3f54328769e7d83681a56281d))
* Support primary keys which are not called 'id' ([14fd890](https://github.com/astrosoftpro/sequelize-hierarchy-next/commit/14fd890d3e245cc5546ef909516db6c7f03d7f3e))
* Tests aimed at Sequelize v4 will also run on v5 ([1331448](https://github.com/astrosoftpro/sequelize-hierarchy-next/commit/1331448bbe2656167a2f207a2b26cdad6e6e9cc9))
* Tests close sequelize connection at end to avoid hang ([a5d15ff](https://github.com/astrosoftpro/sequelize-hierarchy-next/commit/a5d15ff10af5758ebe922d60a7908c601181e71b))
* Tests create `drive` model in correct schema ([7144d58](https://github.com/astrosoftpro/sequelize-hierarchy-next/commit/7144d58964845b7c0d69bcce77aa7c42f02d7620))
* Typo in changelog ([62c86da](https://github.com/astrosoftpro/sequelize-hierarchy-next/commit/62c86da80e351c1d0f9d0ffc0f9b13b1cd446326))
* When deleting instance attributes from `dataValues`, check is a Sequelize Model instance ([2e74f3e](https://github.com/astrosoftpro/sequelize-hierarchy-next/commit/2e74f3ee2deb96bba8a9bafba762bf2e26554471))
* Wrong ordering of children (closes [#32](https://github.com/astrosoftpro/sequelize-hierarchy-next/issues/32)) ([363f455](https://github.com/astrosoftpro/sequelize-hierarchy-next/commit/363f45533e2002cee0c4d72f4135effb9afc2edd))
