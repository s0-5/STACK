# STACK — DoS Simulation & Stress Research Framework

STACK is a **professional research framework** designed to simulate high-intensity Denial-of-Service (DoS) scenarios in **controlled and authorized environments**.

The framework focuses on **understanding system behavior under extreme load**, analyzing degradation patterns, and supporting **defensive security research** and performance planning.

---

## 🎯 Project Purpose

STACK enables researchers and security professionals to:

- Simulate high-volume request floods in isolated lab environments
- Study service saturation and failure thresholds
- Analyze latency behavior and error ratios under stress
- Support defensive capacity planning and resilience research
- Generate structured technical reports for research documentation
- Conduct authorized security testing with comprehensive metrics

---

## 🧠 Framework Architecture

STACK is built with a **scalable, adaptive architecture** that adjusts to the capabilities of the host system. Performance output is intentionally dependent on available hardware resources, ensuring realistic testing scenarios across different environments.

### Core Design Principles

- **Resource-Aware Scaling**: Automatically adapts to available CPU, RAM, and network capacity
- **Multi-Level Performance Modes**: Three distinct operational modes for different testing intensities
- **Real-Time Monitoring**: Continuous tracking of both client and server metrics
- **Professional Reporting**: Comprehensive PDF reports with detailed analytics
- **Safety-First Approach**: Built-in protections to prevent system overload

---

## ⚙️ Performance Modes

STACK operates in three distinct performance modes, each designed for specific research scenarios:

### 🔒 Safe Mode (Recommended)

**Default operational mode** with built-in resource protection:

- **Request Rate Range**: 100 - 1,000 requests per second
- **Thread Count Limit**: Up to 100 concurrent threads
- **Automatic Protection**: CPU and RAM monitoring with auto-stop thresholds
- **Use Case**: Light testing, learning environments, initial assessments
- **System Requirements**: Standard personal computers and workstations

### 🚀 Super Test Mode

**Advanced testing mode** for higher intensity research:

- **Request Rate Range**: 1,000 - 1,000,000 requests per second
- **Thread Count Limit**: Up to 5,000 concurrent threads
- **Protection Status**: Safety limits disabled, manual monitoring required
- **Use Case**: Medium to high-intensity testing, performance evaluation
- **System Requirements**: High-performance workstations or dedicated servers
- **Activation**: Requires explicit user confirmation

### 🔥 THROUGHPUT MAX Mode

**Extreme performance mode** for maximum throughput research:

- **Request Rate Range**: 100,000 - 3,000,000 requests per second
- **Visual Indicators**: Dynamic color-coded slider (yellow warning, red at 1M+)
- **Interface Theme**: Dark red theme to indicate extreme mode
- **Use Case**: High-intensity research, capacity planning, stress testing
- **System Requirements**: Professional-grade hardware (see hardware requirements below)
- **Activation**: Requires Super Test Mode activation and hardware confirmation

#### Hardware Requirements for THROUGHPUT MAX Mode

**Minimum (Limited Operation)**:
- CPU: 6 Cores / 12 Threads
- RAM: 16 GB
- Network: 1 Gbps Stable
- OS: Windows 10/11 or Linux x64
- Storage: SSD

**Recommended (Stable Operation)**:
- CPU: 8-12 Cores / 16-24 Threads
- RAM: 32 GB
- Network: 10 Gbps
- OS: Linux (Preferred) / Windows
- Storage: NVMe SSD

**Professional/Research (High Intensity Testing)**:
- CPU: 16+ Cores / 32+ Threads
- RAM: 64 GB
- Network: 10-25 Gbps
- OS: Linux Server
- Environment: Dedicated / Isolated Test Lab

---

## 📊 Reporting & Analytics

STACK generates **comprehensive professional reports** in PDF format, including:

### Report Contents

- **Target Information**: Host details, target type classification, execution mode
- **Session Metadata**: Unique session hash, test user identification, timestamp
- **Request Analysis**: Total requests, success/failure ratios, request rate statistics
- **Latency Metrics**: Response time percentiles (P50, P95, P99, P99.9)
- **Error Taxonomy**: Categorized error types (timeout, DNS, TLS, HTTP, connection)
- **Server Status Timeline**: Per-second tracking of server response patterns
- **Client System Resources**: CPU, RAM, and GPU usage statistics (average and peak)
- **Server Impact Indicators**: Load assessment and response time analysis
- **Visual Charts**: Timeline graphs showing server status over time

### Report Features

- **Professional Layout**: Structured multi-page PDF format
- **Session Integrity**: Unique hash identifiers for each test session
- **Compliance Documentation**: Legal disclaimers and authorization tracking
- **Export Capabilities**: PDF export with organized file naming

---

## 🛡️ Safety & Enterprise Features

### Target Ownership Confirmation

- **Pre-Execution Verification**: Mandatory confirmation dialog before test initiation
- **Target Type Classification**: Local, Test, or Authorized environment selection
- **Legal Compliance**: Explicit acknowledgment of authorization requirements

### Execution Modes

- **Research Mode**: Lower intensity testing for detailed analysis and discovery
- **Stress Mode**: High intensity testing to evaluate system limits and resilience

### Load Profiles

- **Constant**: Steady, consistent load throughout the test
- **Ramp Up**: Gradual increase in load intensity
- **Steady**: Maintained load after initial ramp-up
- **Ramp Down**: Gradual decrease in load intensity

### Emergency Controls

- **Kill Switch**: Immediate termination of all operations
- **Auto-Stop Protection**: Automatic shutdown when CPU or RAM thresholds are exceeded (Safe Mode)
- **Resource Monitoring**: Real-time tracking of client system resources

---

## 🔍 Port Scanning & Target Discovery

### Scan Types

- **Basic (Fast)**: Quick port discovery for common services
- **Medium (Balanced)**: Comprehensive port scanning with balanced speed
- **Deep (Detailed)**: Thorough port enumeration for complete discovery

### Supported Input Types

- IP Addresses (IPv4)
- Domain names and URLs
- Automatic protocol detection (HTTP/HTTPS)

---

## 📈 Monitoring & Metrics

### Real-Time Monitoring

- **Request Statistics**: Live count of total, successful, and failed requests
- **Rate Tracking**: Current requests per second
- **Time Metrics**: Elapsed test duration
- **Server Status**: Real-time assessment of target server condition
- **Resource Usage**: CPU, RAM, and GPU utilization tracking

### Server Response Analysis

- **Response Time Tracking**: Per-second monitoring of server response times
- **Success Rate Calculation**: Percentage of successful requests
- **Status Classification**: Server status indicators based on response metrics
- **Timeline Visualization**: Graphical representation of server behavior over time

---

## 🖥️ Supported Environments

STACK is architected to operate across a wide range of systems:

- **Personal Computers**: Research and learning scale testing
- **Workstations**: Medium-intensity research scenarios
- **Dedicated Servers**: High-performance testing environments
- **Isolated Lab Environments**: Controlled research facilities

### Performance Factors

Actual performance depends on:
- CPU core count and threading capability
- Available memory (RAM)
- Network capacity and stability
- Operating system constraints and optimizations

---

## 🔐 Security & Compliance

### Authorization Requirements

- **Target Ownership Verification**: Mandatory confirmation before execution
- **Target Type Classification**: Categorization of testing environment
- **Session Tracking**: Unique identifiers for audit and compliance
- **User Identification**: Test user tracking for accountability

### Legal Framework

- **Strict Authorization**: Use only on systems you own or have explicit written permission to test
- **Educational Purpose**: Designed for authorized security testing and research
- **Compliance Documentation**: Built-in legal disclaimers and authorization tracking
- **No Misuse Policy**: Framework explicitly prohibits unauthorized use

---

## 📋 Command-Line Interface

STACK provides command-line options for version and help information:

- `--version`: Display version information and developer details
- `--help`: Show usage information and legal notices

---

## 🖼️ Visual Documentation

This repository includes **illustrative images** showcasing:

- Report layout examples and structure
- Data visualization formats and charts
- Analytical graph styles and presentation
- UI interface design and organization

All images are **demonstrative only** and do not represent real targets, real systems, or live environments.

---

## 🔐 Repository Scope & Restrictions

This repository exists **for documentation and portfolio purposes only**.

- ❌ No source code included
- ❌ No binaries or executables
- ❌ No configuration files
- ❌ No operational instructions or implementation details

---

## ⚖️ Legal & Ethical Notice

STACK is intended **strictly** for:

- **Authorized Security Testing**: Use only on systems you own or have explicit written authorization to test
- **Educational Use**: Learning and understanding system behavior under load
- **Academic and Research Purposes**: Scientific research and defensive security studies

**Unauthorized use, misuse, or deployment outside a permitted environment is strictly prohibited.**

The developer assumes **no responsibility** for any misuse, unauthorized access, or illegal application of this framework.

---

## 🚫 Distribution & Commercial Use

- This framework is **NOT** intended for public release
- It is **NOT** offered for sale or commercial licensing
- Redistribution of the implementation is **not permitted**
- This documentation is provided for informational and portfolio purposes only

---

## 🧾 Project Status

**Version**: v5.3.0  
**Status**: Private Research Project  
**Repository Type**: Documentation-only

---

## 📝 Version Information

**Current Version**: v5.3.0  
**Developer**: Mr.Essam GitHub(s0-5)  
**Copyright**: © 2026

---

© 2026 — STACK Research Framework
