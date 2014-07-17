# OGC Simple Feature Access - SQL 1.2.1 Test-Suite

The OGC Simple Feature Access - SQL 1.2.1 Test-Suite provides the Executable Test Script (ETS) to test implementations against the following specification(s):

OpenGIS Simple Features Specification For SQL, Revision 1.2.1 [OGC
06-104r4](http://portal.opengeospatial.org/files/?artifact_id=25354).

The specification provides the rules to support storage, retrieval, query and update of
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

Detailed information about this test suite is available [here]( http://htmlpreview.github.com/?https://github.com/opengeospatial/ets-sfs12/blob/master/src/main/web/index.html).

## License

[Apache 2.0 License](LICENSE.md)

## Building

This test is build using [Apache Maven](http://maven.apache.org/). To 
build the test suite run maven from the root directory:

```
mvn install
```
     
## Testing an Implementation

For UNIX/OS Users

Clone this repository:
```     
git clone https://github.com/opengeospatial/ets-sfs12.git
```
Run:
```   
build.sh**
```

For Windows users and to get more information about running tests in TEAM Engine, check the instructions at the [CITE wiki](http://cite.opengeospatial.org/easytesting)

## Bugs

Issue tracker is available at [github](https://github.com/opengeospatial/ets-sfs12/issues).

## Mailing Lists

The [cite-forum](http://cite.opengeospatial.org/forum) is where software developers discuss issues and solutions related to OGC tests. 

## More Information

Visit the [CITE website](http://cite.opengeospatial.org/) to get more information about the CITE program and tools.

