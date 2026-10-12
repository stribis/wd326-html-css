# Font Delivery Decision - Example

- Project scenario: A Swiss cultural-organization website with a privacy-first policy.
- Preferred delivery method: Self-hosted Inter variable WOFF2.
- Privacy or legal considerations: No font request is sent to a third party; verify and retain the OFL license.
- Performance considerations: Subset the required character set, preload only when measurement proves it useful, and cache the immutable file.
- Fallback strategy: Arial, Helvetica, then the generic sans-serif family.
- Why this choice fits the project: It removes an external runtime dependency and keeps deployment control with the organization.
