:og:description: LSSTComCam is the commissioning camera for the Vera C. Rubin Observatory.

#########################################
LSSTComCam: The LSST Commissioning Camera
#########################################

*Citation:* SLAC National Accelerator Laboratory & NSF-DOE Vera C. Rubin Observatory, *The LSST Commissioning Camera* (2024) |doi_image| https://doi.org/10.71929/rubin/2561361

The LSST Commissioning Camera (LSSTComCam) was mounted on the Simonyi Survey Telescope in August 2022 and observed for seven weeks in late 2024 until it was removed from the telescope in December 2024.
It is a smaller, fully functional version of `LSSTCam <https://lsstcam.lsst.io>`_, with only the central raft of nine 4k x 4k CCDs (all `ITL <https://www.itl.arizona.edu/capabilities>`_ sensors) and comprising 144 megapixels.
Every CCD has 16 amplifiers, each reading 1 million pixels.
LSSTComCam was designed to enable end-to-end testing of the observatory's systems, including data acquisition, image processing, and observatory operations.
LSSTComCam is also referred to as the engineering test camera or, informally, as ComCam.

.. _comcam-focalplane:

Focal plane
===========

LSSTComCam consists of only a single "raft" of 9 CCDs
(charge-coupled device, also called a sensor, detector, or chip).
Each CCD is 4k x 4k pixels (4000 by 4000 pixels), for a total of 144 Mpix.
For comparison, LSSTCam has 21 rafts, and 189 of the same CCDs.
All of LSSTComCam's CCDs are from ITL, one of the same two vendors that supplied the LSSTCam detectors (ITL and e2v).

.. figure:: /comcam_focal_plane.png
    :name: comcam_focal_plane
    :alt: A visual showing the relative size of the LSST Commmissioning Camera, with just 9 detectors, compared to the LSST Camera with 189 detectors.

    Figure 1: The LSSTComCam has only 9 CCDs compared to LSSTCam's 189 CCDs.


.. _comcam-filters:

Filters
=======

LSSTComCam uses the same *ugrizy* `filters as LSSTCam <https://rubinobservatory.org/for-scientists/rubin-101/instruments>`_.
LSSTComCam's filter exchanger can only hold three physical filters at a time (compared to 5 for LSSTCam).

.. _comcam-keynumbers:

Key numbers
===========

* CCDs: 9
* pixels: 144 Mpix
* platescale: 0.2 arcsec / pixel
* field of view: 40 x 40 arcminutes
* read noise: 6.21 electrons (ITL sensors)
* gain: 1.68 electrons / ADU (ITL sensors)

Visit Rubin Observatory's `Key Numbers <https://rubinobservatory.org/for-scientists/rubin-101/key-numbers>`_ page, and the `page for LSSTCam <https://rubinobservatory.org/for-scientists/rubin-101/instruments>`_, for more key numbers.

.. _comcam-knownissues:

Known issues
============

LSSTComCam was the instrument used to facilitate early system integration for the Rubin Observatory.
It was not, itself, commissioned.
The image quality achieved during the LSSTComCam on-sky campaign, and of the data in `DP1 <https://dp1.lsst.io>`_, is not necessarily indicative of the image quality that Rubin Observatory expects to achieve with LSSTCam.

.. _comcam-citing:

Citing LSSTComCam
=================

Use of the correct formal citation strings and keywords ensures that all uses of data from LSSTComCam can be found using community tools.

* DOI: https://doi.org/10.71929/rubin/2561361 (refers to this document)

  * Use this DOI when referring to the instrument specifically; otherwise a dataset DOI may be more appropriate (see the documentation for the specific data you are using).

* IVOA `ObsCore <https://www.ivoa.net/documents/ObsCore/20170509/index.html>`_ keywords: ``facility_name`` = ``Rubin:Simonyi``, ``instrument_name`` = ``LSSTComCam``
* AAS `facility keyword <https://journals.aas.org/facility-keywords/>`_: ``Rubin:Simonyi`` or, for specificity, ``Rubin:Simonyi (LSSTComCam)``
* Minor Planet Center `observatory code <https://minorplanetcenter.net/iau/lists/ObsCodesF.html>`_: ``X05``

.. _comcam-refs:

References
==========

Additional information is available via:

* `Rubin commissioning camera: integration, functional testing, and lab performance <https://ui.adsabs.harvard.edu/abs/2020SPIE11447E..0LS/abstract>`_, Stalder et al. (2020; SPIE, `doi:10.1117/12.2561132 <https://doi.org/10.1117/12.2561132>`_)
* `Rubin Observatory Commissioning Camera: summit integration <https://ui.adsabs.harvard.edu/abs/2022SPIE12184E..0JS/abstract>`_, Stalder et al. (2022; SPIE, `doi:10.1117/12.2630184 <https://doi.org/10.1117/12.2630184>`_)
* `The LSST commissioning camera status and progress <https://ui.adsabs.harvard.edu/abs/2018SPIE10700E..3DH/abstract>`_, Howard et al. (2018; SPIE, `doi:10.1117/12.2312684 <https://doi.org/10.1117/12.2312684>`_)
* `An interim report on the ComCam on-sky campaign <https://sitcomtn-149.lsst.io/>`_, Vera C. Rubin Observatory (2025; Commissioning Technical Note SITCOMTN-149)
* `LSSTComCam photo gallery <https://rubin.canto.com/v/gallery/library?keyword=ComCam&gSortingForward=false&gOrderProp=uploadDate&viewIndex=2&display=fitView&referenceTo=&from=curatedView>`_

.. image:: https://rubin.canto.com/direct/image/da6v70a8hh0vnc9i732g0i776q/w-FeY5t99VBTklZmjIHVDbCDFfE/original?content-type=image%2Fjpeg&name=P1060554RubinObservatoryComCamM2.jpg
   :width: 75%
   :class: no-scaled-link
   :align: center

This material is based upon work supported in part by the National Science Foundation through Cooperative Agreement AST-1258333 and Cooperative Support Agreement AST-1202910 managed by the Association of Universities for Research in Astronomy (AURA), and the Department of Energy under Contract No. DE-AC02-76SF00515 with the SLAC National Accelerator Laboratory managed by Stanford University.
Additional Rubin Observatory funding comes from private donations, grants to universities, and in-kind support from LSST-DA Institutional Members.
