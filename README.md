# rules-us-ut

Utah tax and benefit rules encoded in Cosilico DSL.

## Structure

```
rules-us-ut/
├── statutes/       # Utah Code encoded rules
└── regulations/    # Utah Administrative Code encoded rules
```

## Overview

This repository contains machine-readable encodings of Utah's tax and benefit laws, including:

- **Utah Code**: State statutes governing taxes, benefits, and related programs
- **Utah Administrative Code**: Regulatory rules implementing state law

## Usage

Rules in this repository are designed to be consumed by the Cosilico Rules as Code (RAC) engine for:

- Policy simulation and microsimulation
- Eligibility determination
- Tax calculation
- Benefit estimation

## Sources

- [Utah Code](https://le.utah.gov/xcode/code.html) - Official Utah state statutes
- [Utah Administrative Code](https://adminrules.utah.gov/) - State regulations

## Related Repositories

- [rac](https://github.com/CosilicoAI/rac) - Core DSL engine
- [rac-us](https://github.com/CosilicoAI/rac-us) - US federal rules
- [arch](https://github.com/CosilicoAI/arch) - Source document archive

## License

Rules are derived from public law. See individual files for source citations.
