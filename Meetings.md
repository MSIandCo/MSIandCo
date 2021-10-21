# Past meetings

## 2021/10/20

The first meeting of the open collaboration provided a brief introduction to mass spectrometry imaging (MSI), why integrating with additional complementary modalities is desirable and the challenges currently faced by practicioners. The open collaboration was introduced, and the initial agenda was outlined. The aims of the collaboration will always be defined by the members, and anyone is welcome to join at any point. Therefore, the initial agenda is likely to evolve as new members join and help to direct the project.

#### Current challenges identified:

* Insufficient registration accuracy
* Inability to compare/use existing registration methods
* Inability to access/share multimodal datasets (limited software tools)

#### Initial aims discussed:

* Regular (every 2-3 months) meetings where data challenges (MSI experts) and algorithms (imaging experts) will be presented
* Collect and publish set of “benchmark” multi-modal data
* Design and develop new format/extension of imzML for multi-modal data
* Evaluate and compare existing registration methods on “benchmark” data

#### Issues raised:

* Possibility of choosing a licence when sharing data
* GDPR, sensitive data and legal/ethical issues related to sharing data

#### Suggestions:

* Possibility of developing a 'human interpretation' evaluation metric for registration, similar to [Ovchinnikova1 et al.](https://link.springer.com/article/10.1186/s12859-020-3425-x).
* Using simulated data as a *ground truth* for evaluating registration techniques. Such simulated data could also potentially be used for [registration directly](https://arxiv.org/pdf/2004.10282.pdf).
* Developing/using model systems as a *ground truth* for evaluating registration techniques, e.g. printed slide or commercial 3D skin model (has layers and are reproducible).
* Building on/itegrating with existing formats used in microscopy (e.g. [OME-TIFF](https://docs.openmicroscopy.org/ome-model/5.6.3/ome-tiff/), [OME-Zarr / NGFF](https://ngff.openmicroscopy.org/latest/))

#### Questionnaire

A short questionnaire was conducted as part of the meeting to understand the audience and to help in designing future aims. The results are included below.

**Q1: What is your background?**

**[58%]** Mass spectrometry imaging expert

**[38%]** Image analysis expert

**[25%]** Other

**Q2: Have you ever encountered problems with image registration so that it influenced the quality of your research?**

**[28%]** Yes, many times

**[68%]** Yes, sometimes

**[8%]** Never

**Q3: Which tools have you used to solve image registration in MSI?**

**[25%]** FlexImaging

**[4%]** HDI imaging

**[4%]** LipostarMSI

**[0%]** M2aia

**[0%]** MSIquant

**[4%]** MSIReader

**[38%]** SCiLS

**[88%]** A programming environment (MATLAB, Python, R, ...)

**[17%]** Any other software

**Q4: Which of the goals of the initiative is your highest priority?**

**[8%]** Create awareness in MSI community for registration issues

**[12%]** Education of MSI community in registration issues

**[0%]** Create awareness in image analysis community for challenges in MSI

**[52%]** Development of new image registration solutions for multimodal MSI

**[8%]** Develop new multimodal compatible MSI data formats

**[20%]** Generation of benchmark datasets

**Q5: Do you have a dataset in mind to share with this initiative?**

**[16%]** Yes

**[72%]** I do not know at this moment

**[12%]** Certainly not

**Q6: Would you like the opportunity to present your data/challenge at a subsequent meeting?**

**[26%]** Yes

**[52%]** Maybe

**[22%]** No
