# SFS 1.2.1 Conformance Test Suite

## Scope

The test suite verifies conformance to _OpenGIS Simple Features Specification
For SQL, Revision 1.2.1_[ (OGC
06-104r4)](http://portal.opengeospatial.org/files/?artifact_id=25354), which
provides provides the rules to support storage, retrieval, query and update of
feature collections via the SQL Call-Level Interface (SQL/CLI). Three
conformance classes are described in the testing guidance document (see [OGC
98-046r2](http://portal.opengeospatial.org/files/?artifact_id=7587)) and in
Annex A Table A1 of OGC 06-104r4.

* SQL Implementation of Feature Tables, Normalized Geometry Schema - SFS (NG) - (gT, b, 2D, N, tN)
* SQL Implementation of Feature Tables, Binary Geometry Schema - SFS (BG) - (gB, b, 2D, N, tN)
* SQL with Geometry Types and Functions Implementation of Feature Tables - SFS (TF) - (gS, b, 2D, N, tN)

Section A.4.1 of 06-104r4 provides more details about the conformance classes
choices (gt,b,2d,N,tn, etc.). The test for these 3 conformance classes are the
same as for [SFS 1.1 OGC
99-049](http://portal.opengeospatial.org/files/?artifact_id=829).

Test suite software [is available (ZIP
archive)](http://portal.opengeospatial.org/files/?artifact_id=16317) for each
of the above alternatives as a set of SQL scripts and as C source code.
Implementers may select either form of test suite for adaptation and testing.

## Release Notes

Release notes are available from the [relnotes.html](relnotes.html).
