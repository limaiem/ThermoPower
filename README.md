# ThermoPower

Free library to model thermal power plants (based on Modelica.Media)

## Library description

The ThermoPower library is a free Modelica library for the dynamic modelling of thermal power plants. The library has been developed to analyse the dynamic behaviour of plants, with the purpose of studying control system strategies and architectures.


A general description of the library can be found in the papers:
 * F. Casella, A. Leva, "[Modelica open library for power plant simulation: design and experimental validation](http://www.modelica.org/Conference2003/papers/h08_Leva.pdf)", Proceedings of the 2003 Modelica Conference, Link&ouml ping, Sweden, 2003.
 * F. Casella, A. Leva, "[Modelling of Thermo-Hydraulic Power Generation Processes Using Modelica](http://dx.doi.org/10.1080/13873950500071082)". Mathematical and Computer Modeling of Dynamical Systems, vol. 12, n. 1, pp. 19-33, Feb. 2006.

ThermoPower 2.1 is the last major revision compatible with Modelica 2.1 and the Modelica Standard Library 2.2.x. The next version is planned to use Modelica 3.x and the Modelica Standard Library 3.x. It will use use stream connectors, which generalize the concept of Flange connectors, lifting the restrictions that only two complementary connectors can be bound.

## Downloads

### Development release

Download [ThermoPower v3.1-beta.0 (2014-06-10)](../../archive/v3.1-beta.0)
* This is a major new release, that has been in the making for 5 years. The new release is not compatible with 2.1. However, models built using the development version of the library after 2011 should compile with little or no adjustments. It has many new features:
  * Use of Modelica 3.2 Revision 2 and Modelica Standard Libary 3.2.1, ensuring full compatibility with all compliant Modelica tools
  * Tested with Dymola and OpenModelica.
Use of stream connectors, compatible with the Modelica.Fluid library, allowing multiple-way connections.
  * Use of the homotopy operator for improved convegence of steady-state initialization problems.
  * Improved Flow1D models with embedded replaceable heat transfer models, allowing a much easier customization of heat transfer correlations
  * Many bug fixes

### Stable releases

* [Version v2.1+msl.2.2.2 (2009-07-06)](../../archive/v2.1+msl.2.2.2.zip)
  *  requires the Modelica Standard Library version 2.2.2

* [Version v2.1+msl.2.2.1 (2009-07-06)](../../archive/v2.1+msl.2.2.1.zip)
  *  requires the Modelica Standard Library version 2.2.1

## License

Copyright &copy; 2002-2014, Politecnico di Milano.

This Modelica package is free software and the use is completely at your own risk;
it can be redistributed and/or modified under the terms of the [Modelica License 2](https://modelica.org/licenses/ModelicaLicense2).

## Development and contribution

Authors:
 * [Francesco Casella](http://home.deib.polimi.it/casella/)
 * Alberto Leva
