# bio
A [Rust](https://www.rust-lang.org/en-US/) crate of strong entities to represent
data relevant to cellular and molecular biology.

## What about algorithms?
Please see [rust-bio](https://github.com/rust-bio/rust-bio). The point of this
crate is to distinguish between what I would like to develop in rust for
bioinformatics/computational biology from what rust-bio attempts to implement and
satisfy.

TL;DR:
* This crate will focus on data representation and manipulation
* Bioinformatics algorithms can be found in rust-bio

# Long Term Goals
Long term goals for this repository include:
* Self development -- learning and understanding how to interact with
  biological data computationally.

* Building up a crate that makes representation easy and efficient both for
  communicating biological data and for processing it.

* Building up enough understanding to formulate the basis for a
  biologically-optimized database. That is, be able to build biological
  entities into a DBMS as first class citizens to make data modelling easier,
  and more standardized.

Speaking a bit more to the last point above, there are always 2 goals that
contend for more attention and focus:
* performance/efficiency
* usability/standardization
Even if biological entities as first class data types does not actually make
data management more efficient and analysis/processing more performant, the
transporting and manipulation of data produced by various organizations can be
managed and implemented much better and more efficiently. I especially have a
particular hate for file formats that try to reduce the dimensionality *and*
the number of files for transferring data, as it makes it incredibly hard to
maintain clean files that are manageable and readable.
