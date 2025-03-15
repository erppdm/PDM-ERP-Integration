### Framework and Future Development

Version **V0.6.0** provides a stable and extensible framework for developing new interfaces and acts as a scalable foundation for future enhancements.

**Introduction**

Efficient data management and seamless integration between PDM and ERP systems are critical for optimising workflows and ensuring consistent data across departments. PDM-ERP Integration addresses these needs by providing a robust, secure, and user-friendly solution that adapts to the company's specific requirements rather than forcing the company to conform to the software.

**PDM-ERP Integration V0.6.0** is a powerful and lightweight solution for:

- Automatic bidirectional data synchronisation between SolidWorks PDM and ERP systems.
- Guaranteed data consistency for data under BiI's responsibility.
- Management of CAD systems not supported by SolidWorks PDM, e.g., Zucken E3.series.
- Merging of different design BOMs before transfer from SolidWorks PDM to ERP.
- Management of CAD-neutral formats (DWG, DXF, PDF, etc.) outside the vault on a file server.
- Management of PDM assemblies in ERP as purchase items without a BOM if the BOM is not needed.
- Implementation of additional tools as needed.

Calculated PDM BOMs as well as CAD BOMs can be used.

The interface is based on an SQL database extended by a PDM add-in. All transactions are stored in the database to guarantee traceability.

To separate master data maintenance between departments, authorisations can be assigned to specific departments. This ensures that data records cannot be changed without authorisation, as data is checked before each storage. These checks can be quickly and easily adapted to new or existing specifications.

PDM-ERP Integration can communicate either directly with the ERP via API or via text files. In both cases, feedback is requested before an action is considered successful or failed.

The PDM-ERP Integration uses the Serial No. Generator to automatically create item numbers. Unique n\:m number ranges are possible, eliminating the need for manual intervention when creating new articles.

In summary, PDM-ERP Integration offers a comprehensive and efficient solution for seamless data exchange and process optimisation between PDM and ERP systems, enhancing productivity and achieving significant reductions in manual effort.

For a brief overview of the workflow and usability, a short [short demonstration](https://github.com/erppdm/PDM-ERP-Integration/blob/8bb438f271238fccce53e02af944d86c6f0888d9/BiI_V0.6.0_in_2%20minutes.mp4) is available to showcase its capabilities in action. The MP4 file cannot be displayed directly and must be downloaded before viewing. The lower screenshot shows the option to download the file.

<p>&nbsp;</p>

![grafik](https://github.com/user-attachments/assets/2a5dde6f-a8ed-4ac9-afc0-4dbc4979ae3d)

