## Introduction

Efficient data management and seamless integration between PDM and ERP systems are essential to optimising workflows and ensuring data consistency across departments. PDM-ERP integration meets these needs by providing a robust, secure and user-friendly solution that adapts to the specific requirements of the company, rather than forcing the company to adapt to the software.

**PDM-ERP Integration V0.6.0** is a powerful and lightweight solution for:

- Automatic bidirectional data synchronisation between SolidWorks PDM and ERP systems.
- Guaranteed data consistency for data under BiI's responsibility.
- Management of CAD systems not supported by SolidWorks PDM, e.g., Zucken E3.series.
- Merging of different design BOMs before transfer from SolidWorks PDM to ERP.
- Management of CAD-neutral formats (DWG, DXF, PDF, etc.) outside the vault on a file server.
- Management of PDM assemblies in ERP as purchase items without a BOM if the BOM is not needed.
- Implementation of additional tools as needed.

Calculated PDM BOMs as well as CAD BOMs can be used.

The interface is based on a SQL database extended by a PDM Add-in. All transactions are stored in the database to guarantee traceability.

To separate master data maintenance between departments, authorisations can be assigned to specific departments. This ensures that data records cannot be changed without authorisation, as data is checked before each storage. These checks can be quickly and easily adapted to new or existing specifications.

**PDM-ERP Integration** can communicate either directly with the ERP via API or via text files. In both cases, feedback is requested before an action is considered successful or failed.

The **PDM-ERP integration** uses the [Serial No. Generator](https://github.com/erppdm/SWSNG) to automatically create item numbers. Unique n:m number ranges are possible, eliminating the need for manual intervention when creating new articles.

In summary, **PDM-ERP Integration** offers a comprehensive and efficient solution for seamless data exchange and process optimisation between PDM and ERP systems, enhancing productivity and achieving significant reductions in manual effort.

For a brief overview of the workflow and usability, a [short demonstration](https://github.com/erppdm/PDM-ERP-Integration/blob/8bb438f271238fccce53e02af944d86c6f0888d9/BiI_V0.6.0_in_2%20minutes.mp4) is available to showcase its capabilities in action.
