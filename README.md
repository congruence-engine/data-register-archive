# Congruence Engine Data Register Archive

An experimental static archive of the [Congruence Engine](https://www.sciencemuseumgroup.org.uk/projects/the-congruence-engine)'s Wikibase-based research data register. This repository is one output of a broader research exploration into Wikibase as infrastructure for managing research project data.

- [Live demo](https://congruence-engine.github.io/data-register-archive)
- [Congruence Engine Data Register (Wikibase instance)](https://congruence-engine.wikibase.cloud)
- [Congruence Engine project](https://www.sciencemuseumgroup.org.uk/projects/the-congruence-engine)

<br />

## About

While Wikimedia Deutschland's commitment to Wikibase.cloud promises long-term platform availability, data preservation remains a consideration for research projects. Humanities infrastructures often outlive individual project cycles, and continuity cannot depend solely on third-party hosting.

This archive was created as an experiment in preserving the Congruence Engine Data Register's information and structure in a static form, ensuring it remains accessible, citable, and recoverable even if the live service changes, migrates, or is discontinued.

The archive was generated using [Snowman](https://github.com/glaciers-in-archives/snowman), an open-source tool developed by the [Glaciers in Archives project](https://github.com/glaciers-in-archives). Snowman offers a way to create static, frozen-in-time copies of data stored in Wikibase instances, preserving the data as it appeared at capture time.

### Limitations

The static nature of this archive imposes several inherent constraints:

**Temporal.** The archive represents a single point in time. It does not reflect subsequent edits, deletions, or additions to the live Wikibase.

**Query.** The snapshot consists of rendered HTML pages with data embedded directly in the markup. Users cannot search, filter, or query the content via SPARQL or API endpoints. While basic search functionality could be implemented using JavaScript, this would require ongoing maintenance as frameworks and libraries evolve.

**Format.** While HTML ensures long-term readability through standard web browsers, it is not immediately reusable as structured data, limiting opportunities for direct data reuse or integration.

### Value as a research tool

Despite these constraints, the archive provides a durable record of the Congruence Engine's Data Register's content and metadata context. It functions as a digital snapshot, preserving the Wikibase instance as a historical artefact of the research data and infrastructure.

As an experiment, this work offered insight into the trade-offs of static archiving for Wikibase instances: what can be preserved, what is lost, and what additional measures might be needed for more comprehensive data preservation.

<br />

## Acknowledgements

### Contributors

* [Kunika Kono](https://github.com/kunika)
* [Felix Needham-Simpson](https://github.com/FelixNeSi)
* [Arran Rees](https://github.com/arranrees)
* [Anna-Maria Sichani](https://github.com/amsichani)
* [Jane Winters](https://github.com/janewinters)

<br />

## License

This work is licensed under [CC0 1.0 Universal (Public Domain Dedication)](https://creativecommons.org/publicdomain/zero/1.0/).
