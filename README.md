# Open Data Toolkit

The Open Data Toolkit is a library for open-source data processing tools to create language model training datasets. This library will integrate [PleIAs](https://huggingface.co/PleIAs)'s existing tools seamlessly into a variety of pipelines. This will also make our tools more readily available to a broader range of users. 

## Existing Tools

*  [OCRonos](https://huggingface.co/PleIAs/OCRonos): an OCR correction model, which removes artifacts from digitization, drastically improving text quality
*  [OCRerrcr](https://huggingface.co/PleIAs/OCRerrcr): OCR error detection model for estimating OCR quality and highlighting errors
*  [Segmentext](https://huggingface.co/PleIAs/Segmentext): segmentation tool, which re-structures text. It identifies and re-formats headings and reconstitute paragraphs, which were split apart during digitization.
*  [Celadon](https://huggingface.co/PleIAs/celadon): a multilingual toxicity classifier that can be used to filter out toxic and harmful content from pretraining datasets
*  [Topical](https://huggingface.co/PleIAs/Topical): topic classification tool, which can be used to curate specialized datasets

## Under Development

*  Vision-language models for PDF segmentation for higher quality text extraction
*  Models for generating synthetic data
*  Additionally, updated OCR correction and topic classification models are being trained


