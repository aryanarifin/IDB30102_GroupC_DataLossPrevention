# Chapter 1: Introduction

## 1.1 Background of the Study
In today's digital enterprise ecosystem, organizations handle massive volumes of sensitive data, including Personal Identifiable Information (PII), proprietary business intelligence, and financial records. The proliferation of remote work, cloud migration, and unauthorized third-party application usage (Shadow IT) has blurred traditional security perimeters. Data Loss Prevention (DLP) systems serve as critical defensive controls designed to detect, monitor, and block sensitive data from unauthorized exfiltration. However, standard rule-based and pattern-matching DLP implementations frequently suffer from high rates of false positives and fail to detect subtle, low-and-slow insider threats.

## 1.2 Problem Statement
1. **Inability to Detect Advanced Insider Threats:** Traditional static DLP mechanisms rely on predefined keywords and regex patterns, making them ineffective at identifying authorized users who gradually exfiltrate sensitive information through non-standard channels or misuse legitimate access rights.
2. **Alert Fatigue from High False-Positive Rates:** Current DLP platforms generate an overwhelming volume of security alerts due to context-unaware inspection of unstructured data across cloud and endpoint environments, leading to security analyst burnout and missed real threats.

## 1.3 Research Aim
To design, implement, and evaluate an adaptive, multi-layered Data Loss Prevention (DLP) framework combining User and Entity Behavior Analytics (UEBA) with automated context-aware data classification to reduce false positives and mitigate insider data exfiltration.

## 1.4 Research Objectives
- **RO1:** To evaluate existing Data Loss Prevention mechanisms and insider threat detection models to identify architectural and operational gaps.
- **RO2:** To design a hybrid DLP framework architecture integrating behavior risk scoring and dynamic document classification.
- **RO3:** To evaluate the detection accuracy, recall, and false-positive reduction rate of the proposed framework using realistic test datasets.
- 
