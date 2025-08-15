# Research Data Analysis & Scientific Paper Writing Expansion Pack

## Overview

This expansion pack transforms BMad Method into a comprehensive research and academic writing system. It provides specialized AI agents for statistical analysis, data visualization, literature review, methodology design, and scientific paper writing across all disciplines including life sciences, physical sciences, social sciences, and engineering.

## Purpose

While the core BMad flow focuses on software development workflows, academic research requires specialized expertise in data analysis, statistical modeling, scientific methodology, and academic writing standards. This expansion pack adds:

- Statistical analysis and data science capabilities
- Scientific methodology design and validation
- Literature review and citation management
- Academic writing and paper structure
- Peer review simulation and quality assurance
- Research ethics and reproducibility validation

## When to Use This Pack

Install this expansion pack when your project requires:

- Statistical analysis of experimental or observational data
- Scientific paper writing and manuscript preparation
- Literature review and systematic reviews
- Research methodology design and validation
- Data visualization for scientific publications
- Grant proposal writing and funding applications
- Peer review preparation and response
- Research ethics and compliance validation

## What's Included

### Agents

- `data-scientist.yaml` - Statistical Analysis & Data Science Expert
- `methodology-designer.yaml` - Research Design & Experimental Methods Expert
- `literature-reviewer.yaml` - Literature Review & Citation Specialist
- `scientific-writer.yaml` - Academic Writing & Publication Expert
- `visualization-specialist.yaml` - Scientific Data Visualization Expert
- `peer-reviewer.yaml` - Peer Review & Quality Assurance Expert
- `research-ethicist.yaml` - Research Ethics & Reproducibility Specialist

### Templates

#### Data Analysis Templates
- `statistical-analysis-plan-tmpl.md` - Statistical Analysis Plan (SAP) template
- `data-analysis-report-tmpl.md` - Comprehensive data analysis report
- `exploratory-data-analysis-tmpl.md` - EDA methodology and reporting

#### Scientific Paper Templates
- `research-paper-tmpl.md` - Standard scientific paper structure
- `systematic-review-tmpl.md` - Systematic review and meta-analysis
- `case-study-tmpl.md` - Clinical or research case study format
- `methods-paper-tmpl.md` - Methodology-focused paper template

#### Grant and Proposal Templates
- `grant-proposal-tmpl.md` - Research grant proposal structure
- `research-protocol-tmpl.md` - Detailed research protocol
- `ethics-application-tmpl.md` - Research ethics committee application

#### Review and Validation Templates
- `peer-review-response-tmpl.md` - Response to peer reviewer comments
- `manuscript-checklist-tmpl.md` - Pre-submission manuscript checklist

### Tasks

#### Data Analysis Workflows
- `data-analysis/design-statistical-plan.md` - Create comprehensive statistical analysis plan
- `data-analysis/perform-exploratory-analysis.md` - Conduct thorough exploratory data analysis
- `data-analysis/validate-assumptions.md` - Test statistical assumptions and model validity
- `data-analysis/interpret-results.md` - Interpret statistical findings scientifically

#### Literature Review Workflows
- `literature/conduct-systematic-search.md` - Systematic literature search methodology
- `literature/screen-papers.md` - Paper screening and selection criteria
- `literature/extract-data.md` - Data extraction and synthesis
- `literature/assess-quality.md` - Study quality assessment and bias evaluation

#### Writing and Publication Workflows
- `writing/structure-manuscript.md` - Organize manuscript sections and flow
- `writing/write-methods-section.md` - Detailed methodology writing
- `writing/write-results-section.md` - Results presentation and statistical reporting
- `writing/write-discussion-section.md` - Discussion, limitations, and conclusions

#### Review and Validation Workflows
- `review/simulate-peer-review.md` - Internal peer review simulation
- `review/validate-reproducibility.md` - Ensure research reproducibility
- `review/check-ethics-compliance.md` - Research ethics compliance validation

### Checklists

- `research-quality-checklist.md` - Comprehensive 20-section research quality validation
- `statistical-analysis-checklist.md` - Statistical methods and reporting checklist
- `manuscript-submission-checklist.md` - Pre-submission manuscript validation
- `data-management-checklist.md` - Research data management and sharing
- `ethics-compliance-checklist.md` - Research ethics and participant protection

### Data Resources

- `statistical-tests-guide.yaml` - Guide for selecting appropriate statistical tests
- `sample-size-calculations.yaml` - Power analysis and sample size methodology
- `citation-formats.yaml` - Citation styles and reference formatting
- `journal-guidelines.yaml` - Common journal submission requirements
- `research-software-tools.yaml` - Recommended software and platforms

## Integration with Core BMad

This expansion pack integrates with the core BMad flow at these points:

1. **Research Planning Phase**: After initial project conception, the methodology designer creates research protocols
2. **Data Collection Phase**: Parallel to data gathering, statistical plans are developed
3. **Analysis Phase**: Data scientists perform statistical analysis and interpretation
4. **Writing Phase**: Scientific writers create manuscripts with visualization specialists
5. **Review Phase**: Peer reviewers validate quality before submission

## Specialized Agents Overview

### Dr. Sarah Chen - Data Scientist
**Expertise**: Statistical analysis, machine learning, data mining, experimental design
- Designs appropriate statistical approaches for research questions
- Performs comprehensive data analysis with proper statistical tests
- Interprets results within scientific context
- Ensures statistical rigor and validity

### Dr. Michael Rodriguez - Methodology Designer  
**Expertise**: Research design, experimental methods, study protocols, causal inference
- Creates robust research methodologies and protocols
- Designs experiments and observational studies
- Validates methodological approaches for research questions
- Ensures scientific rigor in research design

### Dr. Emily Watson - Literature Reviewer
**Expertise**: Systematic reviews, meta-analysis, literature synthesis, citation analysis
- Conducts comprehensive literature searches and reviews
- Performs systematic reviews and meta-analyses
- Manages citations and reference databases
- Synthesizes existing knowledge and identifies research gaps

### Dr. James Park - Scientific Writer
**Expertise**: Academic writing, manuscript preparation, scientific communication, publishing
- Writes clear, structured scientific manuscripts
- Ensures proper academic writing standards and style
- Adapts writing for different audiences and journals
- Manages manuscript submission and revision processes

### Dr. Lisa Thompson - Visualization Specialist
**Expertise**: Scientific data visualization, statistical graphics, publication-ready figures
- Creates compelling and accurate data visualizations
- Designs figures that meet publication standards
- Ensures statistical graphics properly represent data
- Optimizes visualizations for scientific communication

### Dr. Robert Kim - Peer Reviewer
**Expertise**: Manuscript review, quality assessment, scientific evaluation, editorial processes
- Simulates peer review process for internal validation
- Identifies potential weaknesses and areas for improvement
- Ensures manuscripts meet publication standards
- Provides constructive feedback for manuscript improvement

### Dr. Maria Santos - Research Ethicist
**Expertise**: Research ethics, reproducibility, data management, compliance
- Ensures ethical conduct throughout research process
- Validates reproducibility and transparency
- Manages data sharing and privacy considerations
- Ensures compliance with institutional and regulatory requirements

## Installation

To install this expansion pack, run:

```bash
npm run install:expansion research-data-analysis
```

Or manually:

```bash
node tools/install-expansion-pack.js research-data-analysis
```

This will:

1. Copy all files to their appropriate locations in `.bmad-core/`
2. Update team configurations to include research agents
3. Make all research agents available for use
4. Install necessary templates and workflows

## Usage Examples

### 1. Statistical Analysis Planning

Starting a new research project:

```bash
# Using the Data Scientist agent
*design-statistical-plan

# Or directly with agent
npm run agent data-scientist
```

### 2. Literature Review

Conducting a systematic literature review:

```bash
# Literature Reviewer agent
*conduct-systematic-search
*screen-papers
*extract-data
```

### 3. Manuscript Writing

With completed analysis:

```bash
# Scientific Writer agent
*structure-manuscript
*write-methods-section
*write-results-section
*write-discussion-section
```

### 4. Internal Peer Review

Before submission:

```bash
# Peer Reviewer agent
*simulate-peer-review
*validate-reproducibility
```

## Research Workflow Integration

### Phase 1: Research Design
1. **Methodology Designer** creates research protocol
2. **Data Scientist** develops statistical analysis plan
3. **Research Ethicist** validates ethical compliance

### Phase 2: Literature Foundation
1. **Literature Reviewer** conducts systematic search
2. **Literature Reviewer** screens and extracts relevant studies
3. **Scientific Writer** synthesizes background knowledge

### Phase 3: Data Analysis
1. **Data Scientist** performs exploratory data analysis
2. **Data Scientist** executes statistical analysis plan
3. **Visualization Specialist** creates publication figures

### Phase 4: Manuscript Preparation
1. **Scientific Writer** structures and writes manuscript
2. **Visualization Specialist** finalizes figures and tables
3. **Literature Reviewer** validates citations and references

### Phase 5: Quality Assurance
1. **Peer Reviewer** simulates external peer review
2. **Research Ethicist** validates reproducibility
3. **Scientific Writer** prepares final submission

## Team Integration

Research agents can be combined into specialized teams:

- `team-quantitative-research.yaml` - For experimental and statistical research
- `team-qualitative-research.yaml` - For observational and qualitative studies
- `team-systematic-review.yaml` - For literature reviews and meta-analyses
- `team-grant-writing.yaml` - For proposal and funding applications

## Customization

You can customize this expansion pack by:

1. **Modifying statistical templates** for your specific research domain
2. **Adjusting quality checklists** for your institutional requirements
3. **Adding discipline-specific tasks** for specialized methodologies
4. **Creating custom journal templates** for target publications
5. **Integrating with research software** (R, Python, SPSS, etc.)

## Best Practices

### Data Management
- Use structured file naming conventions
- Maintain version control for analysis code
- Document all data transformations and cleaning steps
- Ensure reproducible computational environments

### Statistical Analysis
- Pre-register analysis plans when possible
- Report all conducted analyses, not just significant results
- Use appropriate statistical tests and check assumptions
- Consider multiple comparison corrections when relevant

### Academic Writing
- Follow target journal guidelines precisely
- Use consistent terminology throughout manuscript
- Ensure figures and tables are self-explanatory
- Maintain objective, scientific tone

### Quality Assurance
- Conduct internal peer review before submission
- Validate all statistical claims and calculations
- Ensure reproducibility of all analyses
- Check compliance with reporting guidelines (CONSORT, STROBE, etc.)

## Dependencies

This expansion pack works best when used with:

- Statistical software (R, Python, SPSS, SAS, Stata)
- Reference management tools (Zotero, Mendeley, EndNote)
- Data visualization software (ggplot2, matplotlib, Tableau)
- Version control systems (Git) for analysis code
- Computational notebooks (Jupyter, R Markdown)

## Supported Research Areas

### Life Sciences
- Clinical trials and medical research
- Biological and biomedical studies
- Epidemiological investigations
- Environmental health studies

### Physical Sciences
- Experimental physics and chemistry
- Materials science research
- Environmental and earth sciences
- Mathematical and computational studies

### Social Sciences
- Psychology and behavioral research
- Sociology and anthropology
- Economics and business research
- Education and policy studies

### Engineering
- Engineering design and optimization
- Systems analysis and modeling
- Technology evaluation studies
- Human factors research

## Quality Standards

This expansion pack adheres to:

- **Statistical rigor**: Proper test selection, assumption checking, and interpretation
- **Methodological validity**: Sound research design and execution
- **Reporting transparency**: Complete and honest reporting of methods and results
- **Ethical compliance**: Adherence to research ethics and participant protection
- **Reproducibility**: Documentation enabling replication of results

## Notes

- Research involves real-world data and ethical considerations
- Statistical analysis requires appropriate software and expertise
- Manuscript preparation should follow target journal guidelines
- Always validate results through independent review processes
- Consider institutional and regulatory requirements for your research domain

## Contributing

We welcome contributions to enhance this research expansion pack:

1. **Statistical methods**: Add support for specialized statistical techniques
2. **Research domains**: Create domain-specific templates and workflows
3. **Software integration**: Add support for additional research software
4. **Quality measures**: Enhance checklists and validation procedures
5. **International standards**: Add support for different regional research standards

## Support and Resources

- 📚 **Research Methods Guides**: Comprehensive methodology documentation
- 📊 **Statistical Resources**: Power analysis and test selection guides
- 📝 **Writing Resources**: Academic writing and publication guides
- 🔍 **Review Guidelines**: Peer review and quality assessment criteria
- 🤝 **Community Forum**: Connect with other research professionals

---

_Version: 1.0.0_  
_Compatible with: BMad Method v4+_  
_Last Updated: 2024_

*"Transforming research workflows through AI-assisted methodology, analysis, and scientific writing."*