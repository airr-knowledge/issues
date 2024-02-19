---
name: Define class for CDM template
about: Checklist for CDM Class and Slots
title: Checklist for XXX Class
labels: ''
assignees: ''

---

- [ ] Is the class an entity or a process? Is it an information entity about a material entity/process, or a pure information entity/process?
- [ ] Specify the ontology URI for class. Is there a hierarchy of ontology terms that are relevant?
- [ ] Define the slots for the class. Every slot should have an URI either to an ontology term or schema.org term for its semantics. Is there a hierarchy of terms that are relevant for its semantics?
- [ ] Define the attributes of each slot. Identifier? Required? Data type? Controlled vocabulary or ontology for the values?
- [ ] Define the direct relations to other objects. What is the cardinality of the relation? Is there an ontology URI for the relation?
- [ ] If the class is a process, there should be slots for the inputs/outputs of the process. They may be directly defined in the class or are relations.
- [ ] Should any slots be potential made into a class? Is the class a composite of other classes?

- [ ] Review and approval by each group (ADC, IEDB, IRAD, OGRDB)
