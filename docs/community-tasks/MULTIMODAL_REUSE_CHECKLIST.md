# Multimodal Data Reuse and Linkage Checklist

**Community checklist for documented reuse needs. Not an automatic AI-readiness designation.**

[Contribute a linkage proposal](https://github.com/PhysioVerse-OSE/mps-multimodal-data-standard/issues/new?template=community-contribution.yml) · [View project tasks](https://github.com/PhysioVerse-OSE/mps-multimodal-data-standard/issues)

Apply this checklist to a real public study or an appropriately shareable metadata record. Record what is available and what is missing. Do not create synthetic data or invent missing sample relationships.

## Study Context

Record the source study and version, biological question, model and tissue, experimental groups, and the intended reuse. Keep donor identifiers non-identifying and preserve stated access conditions.

## File and Modality Inventory

| Item to check | Evidence or response | Status |
|---|---|---|
| Source repository, accession or DOI, and record version | To provide | To review |
| Modalities actually available | To provide | To review |
| File formats, raw or processed status, and relevant software | To provide | To review |
| Source file identifiers and file manifest | To provide | To review |
| Feature identities, units, and matrix orientation | To provide | To review |
| Processing history and documented transformations | To provide | To review |
| Acquisition or instrument context needed for reuse | To provide | To review |
| Missing files, missing values, and reported exclusions | To provide | To review |
| Access conditions, reuse terms, and attribution | To provide | To review |

Use Available, Incomplete, Not reported, Not applicable, or Requires authorized access. A public metadata record is not proof that every underlying file is public.

## Original Identifiers and Relationships

| Relationship | Information to record |
|---|---|
| Study to model and experiment | Original study, model, experiment, and version identifiers |
| Donor or biological unit to sample | Permitted non-identifying source identifier and independent experimental unit |
| Sample to assay or file | Original sample ID, assay ID, modality, source file ID, and relationship type |
| Device, compartment, well, or region to observation | The measured entity and the location or region identity |
| Longitudinal measurements | Culture age, exposure-relative time, collection time, units, and reference origins |
| Omics to imaging or sensor data | Whether measurements come from the same sample, a paired sample, a parallel culture, or only the same group |
| Source ID to any harmonized ID | Explicit crosswalk with the original ID retained |

Do not assume that two modalities are paired because they share a donor, treatment label, or nominal time point. Record the stated pairing level and any ambiguity.

## Modality-Specific Context

**Omics:** feature identifiers and version, expression or abundance scale, normalization or processing, sample-level metadata, and batch descriptors when available.

**Imaging and histology:** file and region identifiers, spatial units, channels or stains, acquisition context, annotations, and links to the measured sample when available.

**Video and sensors:** acquisition start and time origin, sampling or frame rate, measurement units, missing intervals, and synchronization information when reported.

**Functional measurements:** assay definition, endpoint and unit, baseline or control definition, time reference, and relationship to other measurements.

These are proposed review prompts, not new requirements imposed on every study.

## Reuse Assessment

State which intended reuse is supported, which requires more information, and which is not supported. Identify any relevant existing data or metadata standard and cite its version. Do not treat checklist completion as proof that a dataset is suitable for every AI or statistical task.

Submit metadata and source links rather than large raw files in public GitHub Issues. Send Mostafa the Issue or Pull Request link after contributing.
