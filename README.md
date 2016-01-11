# awesome-threat-intelligence
A curated list of Awesome Threat Intelligence resources

- [Sources](#sources)
- [Formats](#formats)
- [Frameworks](#frameworks-and-platforms)
- [Tools](#tools)
- [Research, Standards & Books](#research)


## Sources



## Formats

<table>
    <tr>
        <td>
            <a href=https://capec.mitre.org/" target="_blank">CAPEC</a>
        </td>
        <td>
            The Common Attack Pattern Enumeration and Classification (CAPEC) is a comprehensive dictionary and classification taxonomy of known attacks that can be used by analysts, developers, testers, and educators to advance community understanding and enhance defenses.
        </td> 
    </tr>
    <tr>
        <td>
            <a href="https://cyboxproject.github.io/" target="_blank">CybOX</a>
        </td>
        <td>
            The Cyber Observable eXpression (CybOX) language provides a common structure for representing cyber observables across and among the operational areas of enterprise cyber security that improves the consistency, efficiency, and interoperability of deployed tools and processes, as well as increases overall situational awareness by enabling the potential for detailed automatable sharing, mapping, detection, and analysis heuristics.
        </td> 
    </tr>
    <tr>
        <td>
            <a href="http://tools.ietf.org/html/rfc5070" target="_blank">IODEF (RFC5070)</a>
        </td>
        <td>
            The Incident Object Description Exchange Format (IODEF) defines a data representation that provides a framework for sharing information commonly exchanged by Computer Security Incident Response Teams (CSIRTs) about computer security incidents.
        </td> 
    </tr>
    <tr>
        <td>
            <a href="http://tools.ietf.org/html/rfc4765" target="_blank">IDMEF (RFC4765)</a>
        </td>
        <td>
            <i>Experimental</i> - The purpose of the Intrusion Detection Message Exchange Format (IDMEF) is to define data formats and exchange procedures for sharing information of interest to intrusion detection and response systems and to the management systems that may need to interact with them.
        </td> 
    </tr>
    <tr>
        <td>
            <a href="https://maecproject.github.io/" target="_blank">MAEC</a>
        </td>
        <td>
            The Malware Attribute Enumeration and Characterization (MAEC) projects is aimed at creating and providing a standardized language for sharing structured information about malware based upon attributes such as behaviors, artifacts, and attack patterns.
        </td> 
    </tr>
    <tr>
        <td>
            <a href="https://stixproject.github.io/" target="_blank">STIX</a>
        </td>
        <td>
            The Structured Threat Information eXpression (STIX) language is a standardized construct to represent cyber threat information. The STIX Language intends to convey the full range of potential cyber threat information and strives to be fully expressive, flexible, extensible, and automatable. STIX does not only allow tool-agnostic fields, but also provides so-called <i>test mechanisms</i> that provide means for embedding tool-specific elements, including OpenIOC, Yara and Snort.
        </td> 
    </tr>  
    <tr>
        <td>
            <a href="https://taxiiproject.github.io/" target="_blank">TAXII</a>
        </td>
        <td>
            The Trusted Automated eXchange of Indicator Information (TAXII) standard defines a set of services and message exchanges that, when implemented,  enable sharing of actionable cyber threat information across organization and product/service boundaries. TAXII defines concepts, protocols, and message exchanges to exchange cyber threat information for the detection, prevention, and mitigation of cyber threats.
        </td> 
    </tr> 
    <tr>
        <td>
            <a href="http://veriscommunity.net/index.html" target="_blank">VERIS</a>
        </td>
        <td>
            The Vocabulary for Event Recording and Incident Sharing (VERIS) is a set of metrics designed to provide a common language for describing security incidents in a structured and repeatable manner. VERIS is a response to one of the most critical and persistent challenges in the security industry - a lack of quality information. In addition to providing a structuref format, VERIS also collects data from the community to report on breaches in the Verizon Data Breach Investigations Report (<a target="_blank" href="http://www.verizonenterprise.com/DBIR/">DBIR</a>) and publishes this database online at <a target="_blank" href="http://vcdb.org/index.html">http://vcdb.org/index.html</a>.
        </td> 
    </tr>     
</table>

## Frameworks and Platforms

<table>
    <tr>
        <td>
            <a href="https://crits.github.io/" target="_blank">CRITS</a>
        </td>
        <td>
            CRITS is a platform that provides analysts with the means to conduct collaborative research into malware and threats. It plugs into a centralized intelligence data repository, but can also be used as a private instance.
        </td>
    </tr>
    <tr>
        <td>
            <a href="http://django-mantis.readthedocs.org/en/latest/" target="_blank">MANTIS</a>
        </td>
        <td>
            The Model-based Analysis of Threat Intelligence Sources (MANTIS) Cyber Threat Intelligence Management Framework supports the management of cyber threat intelligence expressed in various standard languages, like STIX and CybOX. It is *not* ready for large-scale production though.
        </td>
    </tr>
    <tr>
        <td>
            <a href="http://csirtgadgets.org/collective-intelligence-framework" target="_blank">CIF</a>
        </td>
        <td>
            The Collective Intelligence Framework (CIF) allows you to combine known malicious threat information from many sources and use that information for IR, detection and mitigation. Code available on <a href="https://github.com/csirtgadgets/massive-octo-spice" target="_blank">GitHub</a>.
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://www.enisa.europa.eu/activities/cert/support/incident-handling-automation" target="_blank">IntelMQ</a>
        </td>
        <td>
            IntelMQ is a solution for CERTs for collecting and processing security feeds, pastebins, tweets using a message queue protocol. It's a community driven initiative called IHAP (Incident Handling Automation Project) which was conceptually designed by European CERTs during several InfoSec events. Its main goal is to give to incident responders an easy way to collect & process threat intelligence thus improving the incident handling processes of CERTs.    
        </td>
    </tr>
    <tr>
        <td>
            <a href="http://www.misp-project.org/" target="_blank">MISP</a>
        </td>
        <td>
            The Malware Information Sharing Platform (MISP) is an open source software solution for collecting, storing, distributing and sharing cyber security indicators and malware analysis. 
        </td>
    </tr>
    <tr>
        <td>
            <a href="http://www.openioc.org/" target="_blank">OpenIOC</a>
        </td>
        <td>
            OpenIOC is an open framework for sharing threat intelligence. It is designed to exchange threat information both internally and externally in a machine-digestible format.
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://www.alienvault.com/open-threat-exchange" target="_blank">OTX - Open Threat Exchange</a>
        </td>
        <td>
            AlienVault Open Threat Exchange (OTX) provides open access to a global community of threat researchers and security professionals. It delivers community-generated threat data, enables collaborative research, and automates the process of updating your security infrastructure with threat data from any source.
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://github.com/tripwire/tardis" target="_blank">TARDIS</a>
        </td>
        <td>
            The Threat Analysis, Reconnaissance, and Data Intelligence System (TARDIS) is an open source framework for performing historical searches using attack signatures.
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://www.threatcrowd.org/" target="_blank">ThreatCrowd</a>
        </td>
        <td>
            ThreatCrowd is a system for finding and researching artefacts relating to cyber threats.
        </td>
    </tr>  
    <tr>
        <td>
            <a href="https://developers.facebook.com/docs/threat-exchange/" target="_blank">ThreatExchange</a>
        </td>
        <td>
            Facebook created ThreatExchange so that participating organizations can share threat data using a convenient, structured, and easy-to-use API that provides privacy controls to enable sharing with only desired groups. This project is still in <b>beta</b>.
        </td>
    </tr>  
    <tr>
        <td>
            <a href="https://exchange.xforce.ibmcloud.com/" target="_blank">XFE - X-Force Exchange</a>
        </td>
        <td>
            The X-Force Exhange (XFE) by IBM XFE is a free SaaS product that you can use to search for threat intelligence information, collect your findings, and share your insights with other members of the XFE community.
        </td>
    </tr>
</table>



## Tools

<table>
    <tr>
        <td>
            <a href="https://github.com/mlsecproject/combine" target="_blank">Combine</a>
        </td>
        <td>
            Combine gathers Threat Intelligence Feeds from publicly available sources.
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://www.fireeye.com/services/freeware/ioc-editor.html" target="_blank">IOC Editor</a>
        </td>
        <td>
            A free editor for Indicators of Compromise (IOCs).
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://github.com/mandiant/ioc_writer" target="_blank">ioc_writer</a>
        </td>
        <td>
            Provides a python library that allows for basic creation and editing of OpenIOC objects.
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://github.com/johestephan/ibmxforceex.checker.py" target="_blank">ibmxforceex.checker.py</a>
        </td>
        <td>
            Python client for the IBM X-Force Exchange.
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://github.com/STIXProject/openioc-to-stix" target="_blank">openioc-to-stix</a>
        </td>
        <td>
            Generate STIX XML from OpenIOC XML.
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://github.com/jpsenior/threataggregator" target="_blank">threataggregator</a>
        </td>
        <td>
            ThreatAggregrator aggregates security threats from a number of online sources, and outputs to various formats, including CEF, Snort and IPTables rules.
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://github.com/jiachongzhi/ThreatTracker" target="_blank">ThreatTracker</a>
        </td>
        <td>
            A Python script designed to monitor and generate alerts on given sets of  IOCs indexed by a set of Google Custom Search Engines. 
        </td>
    </tr>     
    <tr>
        <td>
            <a href="https://github.com/mlsecproject/tiq-test" target="_blank">tiq-test</a>
        </td>
        <td>
            The Threat Intelligence Quotient (TIQ) Test tool provides visualization and statistical analysis of TI feeds.
        </td>
    </tr>
</table>



## <a name="research"></a>Research, Standards & Books

<table>
    <tr>
        <td>
            <a href="https://cryptome.org/2015/09/cti-guide.pdf" target="_blank">Definitive Guide to Cyber Threat Intelligence</a>
        </td>
        <td>
            Describes the elements of cyber threat intelligence and discusses how it is collected, analyzed, and used by a variety of human and technology consumers.Fruther examines how intelligence can improve cybersecurity at tactical, operational, and strategic levels, and how it can help you stop attacks sooner, improve your defenses, and talk more productively about cybersecurity issues with executive management in typical <i>for Dummies</i> style.
        </td>
    </tr>
    <tr>
        <td>
            <a href="http://csrc.nist.gov/publications/drafts/800-150/sp800_150_draft.pdf" target="_blank">Guide to Cyber Threat Information Sharing by NIST</a>
        </td>
        <td>
            The Guide to Cyber Threat Information Sharing (NIST Special Publication 800-15, draft) assists organizations in establishing computer security incident response capabilities that leverage the collective knowledge, experience, and abilities of their partners by actively sharing threat intelligence and ongoing coordination. The guide provides guidelines for coordinated incident handling, including producing and consuming data, participating in information sharingcommunities, and protecting incident-related data.
        </td>
    </tr>
</table>
