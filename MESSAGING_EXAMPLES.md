# Messaging Examples & Templates

This document provides approved messaging examples for different audiences and use cases.

## Elevator Pitches

### 30-Second Version
"status.health provides health verification infrastructure that enables businesses to verify health information without storing any protected health data. Using zero-knowledge proofs and on-device processing, we eliminate HIPAA liability while providing cryptographic proof of health facts. Zero data stored means zero risk of breach."

### 10-Second Version
"We enable health verification without data storage. Businesses verify health facts without HIPAA liability. Zero data, zero risk."

## Audience-Specific Messaging

### For Identity Verification Platforms

#### Value Proposition
"Add health verification to your KYC flow without becoming a HIPAA-covered entity."

#### Technical Description
"Our API enables your platform to request health verifications that process entirely on users' devices. You receive only cryptographic proofs—never PHI. No BAA required."

#### Use Case Example
"Enable age verification, vaccination status, or health clearances as additional identity attributes without storing or processing health data."

### For Insurance Carriers

#### Value Proposition
"Verify wellness milestones and health metrics for premium adjustments without PHI liability."

#### Technical Description
"Members verify health facts through on-device processing. Your systems receive only binary confirmations or range validations—never raw health data."

#### Use Case Example
"Confirm annual physicals, vaccination status, or wellness program participation without creating data breach risk."

### For Dating Platforms

#### Value Proposition
"Enable health verification badges without storing sensitive user data or creating regulatory liability."

#### Technical Description
"Users verify their health status on their own devices. Your platform displays verification badges based on cryptographic proofs, not health records."

#### Use Case Example
"Offer STI testing verification badges that update automatically while maintaining complete user privacy."

### For Clinical Research

#### Value Proposition
"Verify protocol compliance and eligibility without handling PHI."

#### Technical Description
"Participants prove eligibility criteria and ongoing compliance through zero-knowledge proofs. Maintain audit trails without data exposure."

#### Use Case Example
"Confirm participants meet inclusion criteria and maintain required testing schedules without accessing their medical records."

## Technical Explanations

### How Zero-Knowledge Proofs Work (Simple)
"Zero-knowledge proofs allow someone to prove a fact without revealing the underlying data. Like proving you're over 21 without showing your birthdate."

### How Zero-Knowledge Proofs Work (Technical)
"Our system generates cryptographic proofs on the user's device that validate specific health facts. The proof can be verified mathematically without access to the source data, similar to how password hashes prove knowledge without storing passwords."

### On-Device Processing Explanation
"All sensitive operations—OCR, data extraction, proof generation—occur on the user's device. Our servers never receive, process, or store health information. We only handle cryptographic proofs that cannot be reversed to reveal health data."

## Common Questions & Approved Responses

### "How is this HIPAA compliant?"
"We never create, receive, maintain, or transmit protected health information. Without PHI, we're not a covered entity or business associate under HIPAA. It's compliant by design—you can't violate rules about data you never touch."

### "How do you verify without seeing the data?"
"Verification happens on the user's device using their camera or health app connections. Their device generates a cryptographic proof that we can validate without seeing the underlying information. It's like checking a digital signature without reading the document."

### "What about data breaches?"
"You can't breach data you don't have. Our architecture ensures health information never leaves the user's device. Even if our entire infrastructure was compromised, there's no health data to steal."

### "How is this different from other verification services?"
"Traditional services store and process health data, creating liability. We process everything on-device and work only with cryptographic proofs. Others are data processors; we're a verification infrastructure that never touches data."

## Brand Descriptions

### One-Liner
"Enterprise health verification infrastructure with zero data storage."

### Short Description (50 words)
"status.health provides privacy-preserving health verification infrastructure for enterprises. Using zero-knowledge proofs and on-device processing, businesses can verify health information without storing PHI or creating HIPAA liability. Our patent-pending technology enables compliance by design: zero data stored means zero risk."

### Medium Description (100 words)
"status.health is enterprise infrastructure for health verification without data storage. Our patent-pending technology enables businesses to verify health facts—from vaccination status to lab results—without creating regulatory liability. 

Using zero-knowledge proofs and on-device processing, sensitive data never leaves users' devices. Businesses receive only cryptographic verifications, eliminating HIPAA compliance burden and breach risk. 

Built for identity platforms, insurers, employers, and healthcare organizations, status.health provides the technical foundation for privacy-preserving health verification at scale. Zero data storage means zero risk—compliance through architecture, not policy."

### Long Description (200 words)
"status.health provides enterprise-grade infrastructure for health verification without the liability of handling protected health information. Our patent-pending technology enables businesses across industries—from identity verification to insurance—to incorporate health facts into their decision-making without becoming HIPAA-regulated entities.

The platform leverages zero-knowledge cryptography and on-device processing to ensure health data never leaves users' control. Through three verification methods—on-device OCR, direct health platform integrations, and local AI processing—users can prove health facts while maintaining complete privacy. 

Businesses receive only cryptographic proofs that validate specific facts without revealing underlying data. This architectural approach eliminates the need for Business Associate Agreements, removes data breach risk, and simplifies compliance across HIPAA, GDPR, and state privacy laws.

With 98% lower operational costs than traditional verification services and the ability to scale without data infrastructure, status.health enables new use cases previously impossible under traditional privacy frameworks. From insurance wellness programs to clinical trial eligibility, our infrastructure makes health verification as simple as payment processing—without the regulatory complexity.

Zero data stored means zero risk. Privacy through math, not policy."

## Writing Style Guidelines

### Technical Accuracy
- Be precise with technical terms
- Don't oversimplify cryptographic concepts
- Use "zero-knowledge proofs" not "encryption" 
- Say "on-device" not "local" or "client-side"

### Compliance Language
- Never claim to be "HIPAA certified" (no such thing)
- Say "HIPAA compliant by design" or "eliminates HIPAA liability"
- Don't make medical claims or offer health advice
- Avoid terms like "diagnosis" or "treatment"

### Business Focus
- Lead with business value, not technology
- Emphasize liability reduction and compliance
- Use concrete examples from target industries
- Quantify benefits when possible (98% cost reduction, etc.)

## Prohibited Messaging

### Never Say
- "We store health data securely" (we don't store it at all)
- "HIPAA certified" (certification doesn't exist)
- "Anonymous health data" (we don't have any health data)
- "Encrypted health records" (we don't have records)
- "Medical device" or "diagnostic tool" (we're infrastructure)

### Never Imply
- That we provide medical advice
- That we can diagnose conditions
- That we store any health information
- That we're a healthcare provider
- That we're a replacement for medical care

---

© 2025 Health Protocol Labs, SPC. All rights reserved.