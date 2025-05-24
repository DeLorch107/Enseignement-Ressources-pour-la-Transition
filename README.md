# Spodumene Project Data Export Tool

A web-based tool for exporting lithium spodumene project data to Excel format for analysis and comparison.

## 📋 Project Overview

This tool processes technical and economic data from three major lithium spodumene concentrate projects:
- **Mt. Holland** (Covalent Lithium - SQM & Wesfarmers)
- **Ewoyaa** (Atlantic Lithium) 
- **Grota do Cirilo** (Sigma Lithium)

The data focuses on SC6-type concentrate production (approximately 6% Li₂O) and enables comparative analysis across different processing approaches and economic models.

## 🚀 Features

- **Interactive Web Interface** - Clean, modern UI for data preview and export
- **Multi-Worksheet Excel Export** - Organized data across 11 separate worksheets
- **Comprehensive Dataset** - Technical specifications, processing methods, and economic metrics
- **Ready-to-Analyze Format** - Structured for pivot tables, charts, and financial modeling
- **Reference Preservation** - All page references and data sources maintained

## 📊 Data Categories

### Technical Analysis
- **Crushing Systems** - Technology comparison (HPGR, multi-stage crushing)
- **Processing Methods** - Grinding, DMS, flotation, magnetic separation
- **Advanced Features** - Specialized equipment (reflux classifiers, upflow classification)
- **Ore Characteristics** - Work index data and liberation properties
- **Product Performance** - Grade targets and recovery rates

### Resource Consumption
- **Energy Requirements** - Power consumption specifications
- **Water Consumption** - Process water usage data
- **Reagents & Consumables** - Chemical requirements and environmental impact

### Economic Analysis
- **CAPEX Analysis** - Capital expenditure breakdown by project phase
- **OPEX Analysis** - Operating expenditure comparison with different cost bases
- **Summary Comparison** - High-level strategic assessment

## 🛠️ How It Works

### Data Processing Pipeline
1. **Source Data** - Extracted from OCR-processed technical reports
2. **Data Structuring** - Organized into comparable categories and metrics
3. **Web Interface** - Preview tables and export functionality
4. **Excel Generation** - Client-side Excel file creation using SheetJS library

### Technology Stack
- **Frontend**: HTML5, CSS3, JavaScript
- **Excel Export**: SheetJS (XLSX.js) library
- **Styling**: Custom CSS with modern design principles
- **Data Processing**: Client-side JavaScript arrays and objects

## 📁 File Structure

```
spodumene-data-export/
├── index.html          # Main application file
├── README.md          # This documentation
└── assets/            # (Optional) Additional resources
    └── sample_data/   # Sample output files
```

## 🔧 Installation & Usage

### Option 1: Direct Usage
1. Download the `index.html` file
2. Open in any modern web browser
3. Click "Download Excel File" to export data

### Option 2: Web Server
1. Clone this repository
2. Serve the HTML file using any web server:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Node.js (with http-server)
   npx http-server
   
   # PHP
   php -S localhost:8000
   ```
3. Access via `http://localhost:8000`

### Option 3: GitHub Pages
1. Fork this repository
2. Enable GitHub Pages in repository settings
3. Access via `https://yourusername.github.io/repository-name`

## 📋 Excel Output Details

### Worksheet Structure
| Worksheet | Content | Rows | Purpose |
|-----------|---------|------|---------|
| Crushing Systems | Technology comparison | 4 | Processing method analysis |
| Processing Methods | DMS, flotation, grinding | 4 | Technical comparison |
| Advanced Features | Specialized equipment | 4 | Innovation assessment |
| Work Index | Bond Work Index data | 4 | Ore hardness comparison |
| Product Performance | Grade & recovery targets | 6 | Production optimization |
| Energy Requirements | Power consumption | 4 | Energy cost analysis |
| Water Consumption | Process water usage | 4 | Environmental impact |
| Reagents Consumables | Chemical requirements | 4 | Operating cost factors |
| CAPEX Analysis | Capital expenditure | 5 | Investment comparison |
| OPEX Analysis | Operating expenditure | 5 | Cost structure analysis |
| Summary Comparison | Strategic overview | 7 | Decision support |

### Data Quality Indicators
- **N/S**: Not Specified in source documents
- **(est.)**: Estimated or derived from broader figures
- **Ref**: Page reference in original OCR reports

## 🎯 Use Cases

### Mining Industry Applications
- **Project Comparison** - Benchmarking different lithium projects
- **Investment Analysis** - CAPEX/OPEX evaluation for funding decisions
- **Technical Assessment** - Processing technology selection
- **Due Diligence** - Comprehensive project evaluation

### Academic & Research
- **Case Study Analysis** - Comparative mining project studies
- **Economic Modeling** - Cost structure analysis
- **Technology Assessment** - Processing method effectiveness
- **Industry Benchmarking** - Performance metrics comparison

### Business Intelligence
- **Market Analysis** - Competitive landscape assessment
- **Strategic Planning** - Technology roadmap development
- **Risk Assessment** - Project viability evaluation
- **Supply Chain Analysis** - Lithium concentrate supply evaluation

## 🔍 Data Sources & Methodology

### Source Documents
Data extracted from technical feasibility studies and project reports:
- Mt. Holland: Integrated mine-concentrator-refinery project documentation
- Ewoyaa: DMS-focused processing approach studies
- Grota do Cirilo: Multi-phase development project reports

### Data Extraction Process
1. **OCR Processing** - Technical reports converted to searchable text
2. **Manual Validation** - Cross-referencing data points across documents
3. **Standardization** - Common units and metrics applied
4. **Quality Control** - Reference verification and data integrity checks

### Limitations & Considerations
- Some data points unavailable due to confidentiality or report scope
- Different reporting standards across projects may affect comparability
- Economic data reflects reporting period conditions (exchange rates, costs)
- Technical specifications may represent design targets rather than achieved performance

## 🤝 Contributing

We welcome contributions to improve data accuracy, add new projects, or enhance functionality:

1. **Data Updates** - Submit corrections or additional project data
2. **Feature Requests** - Suggest new analysis capabilities
3. **Bug Reports** - Report issues with data export or display
4. **Documentation** - Improve guides and explanations

### Contribution Guidelines
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit changes (`git commit -am 'Add new feature'`)
4. Push to branch (`git push origin feature/improvement`)
5. Create Pull Request with detailed description

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Support & Contact

For questions, issues, or collaboration opportunities:
- **Issues**: Use GitHub Issues for bug reports and feature requests
- **Discussions**: Use GitHub Discussions for general questions
- **Email**: [Your contact information]

## 🔄 Version History

### v1.0.0 (Current)
- Initial release with three major lithium projects
- 11 comprehensive data worksheets
- Modern web interface with export functionality
- Complete technical and economic dataset

### Planned Features
- [ ] Additional lithium projects integration
- [ ] Real-time data updates from public sources
- [ ] Advanced filtering and search capabilities
- [ ] Custom report generation
- [ ] Data visualization dashboard
- [ ] API endpoints for programmatic access

## 📈 Project Metrics

- **Projects Analyzed**: 3 major lithium operations
- **Data Points**: 100+ technical and economic metrics
- **Worksheets Generated**: 11 structured data tables
- **Processing Methods**: 4 major technology approaches
- **Economic Analysis**: CAPEX/OPEX across 5 project phases

---

*This tool is designed for professional analysis of lithium mining projects and should be used in conjunction with additional due diligence and expert consultation for investment or operational decisions.*
