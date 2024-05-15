# Voting - Files related to the NIST Voting program.

This repository holds information associated with the NIST Voting Program.  It currently holds information about the election common data format (CDF) project and related information and files that are being created by NIST and collaborators.

NIST's election CDF project has the goal of (a) specifying a common import/export format for election devices such as electronic pollbooks, election management systems, and vote capture devices, and (b) specifying a comprehensive foundational UML models that will cover election data in general.  The model defines the various objects (e.g., candidates, contests, offices, etc.) and their associated attributes, and specifies the relationships between and among the objects.  It includes a glossary and other tools to ensure that the implementations of the model (e.g., XML or JSON formats) are consistent in style, definition, and composition.

There is an election glossary of terms, many of which are used in VVSG 2.0, located at https://pages.nist.gov/ElectionGlossary/

There are currently 8 CDF projects under active development, located in the following repositories:

1. Ballot Definition - created by EMSs to support interoperable ballot styles that can be read by scanners - the repository is located at https://github.com/usnistgov/BallotDefinition.
2. Cast Vote Records - created by scanners or DREs, contain tabulatable voter choices - the repository is located at https://github.com/usnistgov/CastVoteRecords.
3. CDF Test Method - An executable test method for determining conformance to CDF specifications, including related test data - the repository is located at https://github.com/usnistgov/cdf-test-method.
4. Election Event Logging - election-related events logged by election devices - the repository is located at https://github.com/usnistgov/ElectionEventLogging.
5. Election Results Reporting - pre- and post-election information and results - the repository is located at https://github.com/usnistgov/ElectionResultsReporting.
6. microCDF - serialization for interoperability of machine readable data in space-constrained environments (e.g. paper) - the repository is located at https://github.com/usnistgov/mcdf
7. Voter Records Interchange - voter registration-related information to support voter registration, electronic pollbooks, and voter registration database exchanges - the repository is located at https://github.com/usnistgov/VoterRecordsInterchange.

Please contact the [NIST Voting Team](mailto:voting@nist.gov) with questions and for more information

There are additionally two other CDF-related projects under active development:

8. Election Business Process Modeling - for defining and modeling election processes for the purposes of informing use case development for CDF projects and showing where interoperability between processes may be beneficial and worthwhile to pursue - the repository is located at https://github.com/usnistgov/ElectionModeling. Contact [John Dziurlaj](mailto:john@turnout.rocks) for questions and more information.
9. Voting Methods - for defining a standard, specification and reference consisting of rigorously and precisely defined models of voting methods or modules including counting, tabulation, mathematical evaluation, and, common operations on vote data sets to support Data Interoperability - the repository is located at https://github.com/usnistgov/VotingMethods. Contact [Lauren Massa-Lochridge](mailto:lauren.massa.lochridge.sf@gmail.com) for questions and answers.
