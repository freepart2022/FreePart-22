# Analyzed CVEs

## List of Analyzed CVEs

We conduct a brief study of all the publicly available CVEs related to data processing frameworks that FreePart supports.

| **ID** | **Framework** | **CVE**        | **API Type**    | **Vulnerable API/Variable**                    |
|--------|---------------|----------------|-----------------|------------------------------------------------|
|    1   |     OpenCV    | CVE-2019-5064  | Data Loading    | CV_FS_MAX_LEN                                  |
|    2   |     OpenCV    | CVE-2019-5063  | Data Loading    | CV_FS_MAX_LEN                                  |
|    3   |     OpenCV    | CVE-2019-14493 | Data Loading    | cv::XMLParser::parse()                         |
|    4   |     OpenCV    | CVE-2019-14492 | Data processing | HaarEvaluator::OptFeature::calc()              |
|    5   |     OpenCV    | CVE-2019-14491 | Data processing | cv::predictOrdered<cv::HaarEvaluator>          |
|    6   |     OpenCV    | CVE-2018-5269  | Data Loading    | cv::RBaseStream::setPos()                      |
|    7   |     OpenCV    | CVE-2018-5268  | Data Loading    | cv::Jpeg2KDecoder::readComponent8u()           |
|    8   |     OpenCV    | CVE-2017-18009 | Data Loading    | cv::HdrDecoder::checkSignature()               |
|    9   |     OpenCV    | CVE-2017-17760 | Data Loading    | cv::PxMDecoder::readData()                     |
|   10   |     OpenCV    | CVE-2017-14136 | Data Loading    | FillColorRow1()                                |
|   11   |     OpenCV    | CVE-2017-12864 | Data Loading    | ReadNumber()                                   |
|   12   |     OpenCV    | CVE-2017-12863 | Data Loading    | PxMDecoder::readData()                         |
|   13   |     OpenCV    | CVE-2017-12862 | Data Loading    | AutoBuffer                                     |
|   14   |     OpenCV    | CVE-2017-12606 | Data Loading    | FillColorRow4()                                |
|   15   |     OpenCV    | CVE-2017-12605 | Data Loading    | FillColorRow8()                                |
|   16   |     OpenCV    | CVE-2017-12604 | Data Loading    | FillUniColor()                                 |
|   17   |     OpenCV    | CVE-2017-12602 | Data Loading    | PxMDecoder::readData()                         |
|   18   |     OpenCV    | CVE-2017-12600 | Data Loading    | PxMDecoder::readData()                         |
|   19   |     OpenCV    | CVE-2017-12599 | Data Loading    | icvCvt_BGRA2BGR_8u_C4C3R()                     |
|   20   |     OpenCV    | CVE-2017-12598 | Data Loading    | cv::RBaseStream::readBlock()                   |
|   21   |     OpenCV    | CVE-2017-12597 | Data Loading    | FillColorRow1()                                |
|   22   |     OpenCV    | CVE-2016-1517  | Data Loading    | faces.size( )                                  |
|   23   |     Pillow    | CVE-2022-24303 | Visualizing     | im.show()                                      |
|   24   |     Pillow    | CVE-2022-22817 | Data processing | PIL.ImageMath.eval()                           |
|   25   |     Pillow    | CVE-2022-22816 | Data Loading    | path_getbbox(), ImagePath.Path                 |
|   26   |     Pillow    | CVE-2022-22815 | Data Loading    | path_getbbox(), ImagePath.Path                 |
|   27   |     Pillow    | CVE-2021-34552 | Data processing | convert()                                      |
|   28   |     Pillow    | CVE-2021-28678 | Data Loading    | BlpImagePlugin()                               |
|   29   |     Pillow    | CVE-2021-28677 | Data Loading    | EPSImageFile                                   |
|   30   |     Pillow    | CVE-2021-28676 | Data processing | FliDecode()                                    |
|   31   |     Pillow    | CVE-2021-28675 | Data Loading    | Image.open()                                   |
|   32   |     Pillow    | CVE-2021-27923 | Data Loading    | PngImagePlugin.PngImageFile()                  |
|   33   |     Pillow    | CVE-2021-27922 | Data Loading    | Jpeg2KImagePlugin.Jpeg2KImageFile(             |
|   34   |     Pillow    | CVE-2021-27921 | Data Loading    | JpegImageFile()                                |
|   35   |     Pillow    | CVE-2021-25293 | Data processing | expandrow()                                    |
|   36   |     Pillow    | CVE-2021-25292 | Data Loading    | read_pdf_info()                                |
|   37   |     Pillow    | CVE-2021-25291 | Data processing | TiffreadRGBATile()                             |
|   38   |     Pillow    | CVE-2021-25290 | Data processing | _TIFFmemcpy()                                  |
|   39   |     Pillow    | CVE-2021-25289 | Data processing | ImagingLibTiffDecode()                         |
|   40   |     Pillow    | CVE-2020-5313  | Data Loading    | ImagingFliDecode()                             |
|   41   |     Pillow    | CVE-2020-5312  | Data Loading    | ImagingPcxDecode()                             |
|   42   |     Pillow    | CVE-2020-5311  | Data Loading    | expandrow()                                    |
|   43   |     Pillow    | CVE-2020-5310  | Data Loading    | ImagingLibTiffDecode()                         |
|   44   |     Pillow    | CVE-2020-35655 | Data Loading    | ImagingSgiRleDecode()                          |
|   45   |     Pillow    | CVE-2020-35654 | Data Loading    | _decodeStripYCbCr()                            |
|   46   |     Pillow    | CVE-2020-35653 | Data Loading    | ImagingPcxDecode()                             |
|   47   |     Pillow    | CVE-2020-11538 | Data Loading    | expandrow()                                    |
|   48   |     Pillow    | CVE-2020-10994 | Data Loading    | j2k_decode_entry()                             |
|   49   |     Pillow    | CVE-2020-10379 | Data Loading    | ReadTile()                                     |
|   50   |     Pillow    | CVE-2020-10378 | Data Loading    | ImagingPcxDecode()                             |
|   51   |     Pillow    | CVE-2020-10177 | Data Loading    | ImagingFliDecode()                             |
|   52   |     Pillow    | CVE-2019-19911 | Data Loading    | _open_index()                                  |
|   53   |     Pillow    | CVE-2019-16865 | Data Loading    | Image.getexif()                                |
|   54   |     Pillow    | CVE-2016-9190  | Data Loading    | ImagingNew()                                   |
|   55   |     Pillow    | CVE-2016-9189  | Data Loading    | PyImaging_MapBuffer()                          |
|   56   |     Pillow    | CVE-2016-4009  | Data processing | ImagingResampleHorizontal()                    |
|   57   |     Pillow    | CVE-2016-3076  | Data Loading    | j2k_encode_entry()                             |
|   58   |     Pillow    | CVE-2016-2533  | Data Loading    | ImagingPcdDecode()                             |
|   59   |     Pillow    | CVE-2016-0775  | Data Loading    | ImagingFliDecode()                             |
|   60   |     Pillow    | CVE-2016-0740  | Data Loading    | ImagingLibTiffDecode()                         |
|   61   |     Pillow    | CVE-2014-9601  | Data Loading    | chunk_iCCP()                                   |
|   62   |     Pillow    | CVE-2014-3598  | Data Loading    | Jpeg2KImageFile()                              |
|   63   |     Pillow    | CVE-2014-3589  | Data Loading    | __init__()                                     |
|   64   |     Pillow    | CVE-2014-3007  | Data Loading    | load_djpeg()                                   |
|   65   |     Pillow    | CVE-2014-1933  | Data Loading    | load_djpeg() and Ghostscript()                 |
|   66   |     Pillow    | CVE-2014-1932  | Data Loading    | load_djpe(), Ghostscript(), load() amd _copy() |
|   67   |     Numpy     | CVE-2017-12852 | Data processing | pad()                                          |
|   68   |     Numpy     | CVE-2014-1859  | Data Loading    | test_open_with_filename()                      |
|   69   |     Numpy     | CVE-2014-1858  | Data Loading    | compile()                                      |
|   70   | Tensorflow    | CVE-2022-23568 | Data processing | AddManySparseToTensorsMap                      |
|   71   | Tensorflow    | CVE-2022-23567 | Data processing | TensorShape                                    |
|   72   | Tensorflow    | CVE-2022-21740 | Data processing | SparseCountSparseOutput                        |
|   73   | Tensorflow    | CVE-2022-21739 | Data processing | QuantizedMaxPool                               |
|   74   | Tensorflow    | CVE-2022-21738 | Data processing | SparseCountSparseOutput                        |
|   75   | Tensorflow    | CVE-2022-21737 | Data processing | Bincount                                       |
|   76   | Tensorflow    | CVE-2022-21736 | Data processing | SparseTensorSliceDataset                       |
|   77   | Tensorflow    | CVE-2022-21735 | Data processing | FractionalMaxPool                              |
|   78   | Tensorflow    | CVE-2022-21734 | Data processing | MapStage                                       |
|   79   | Tensorflow    | CVE-2022-21733 | Data processing | StringNGrams                                   |
|   80   | Tensorflow    | CVE-2022-21732 | Data processing | ThreadPoolHandle                               |
|   81   | Tensorflow    | CVE-2022-21731 | Data processing | ConcatV2                                       |
|   82   | Tensorflow    | CVE-2022-21730 | Data processing | FractionalAvgPoolGrad                          |
|   83   | Tensorflow    | CVE-2022-21729 | Data processing | UnravelIndex                                   |
|   84   | Tensorflow    | CVE-2022-21728 | Data processing | ReverseSequence                                |
|   85   | Tensorflow    | CVE-2022-21727 | Data processing | Dequantize                                     |
|   86   | Tensorflow    | CVE-2022-21726 | Data processing | Dequantize                                     |
|   87   | Tensorflow    | CVE-2022-21725 | Data processing | AvgPoolGrad                                    |
|   88   | Tensorflow    | CVE-2021-41226 | Data processing | SparseBinCount                                 |
|   89   | Tensorflow    | CVE-2021-41224 | Data processing | SparseFillEmptyRows                            |
|   90   | Tensorflow    | CVE-2021-41223 | Data processing | FusedBatchNorm                                 |
|   91   | Tensorflow    | CVE-2021-41222 | Data processing | SplitV                                         |
|   92   | Tensorflow    | CVE-2021-41221 | Data processing | Cudnn                                          |
|   93   | Tensorflow    | CVE-2021-41219 | Data processing | SparseMatMul                                   |
|   94   | Tensorflow    | CVE-2021-41218 | Data processing | AllToAll                                       |
|   95   | Tensorflow    | CVE-2021-41217 | Data processing | Exit                                           |
|   96   | Tensorflow    | CVE-2021-41216 | Data processing | Transpose                                      |
|   97   | Tensorflow    | CVE-2021-41215 | Data processing | DeserializeSparse                              |
|   98   | Tensorflow    | CVE-2021-41214 | Data processing | raggedcross                                    |
|   99   | Tensorflow    | CVE-2021-41213 | Data processing | tf.function                                    |
|   100  | Tensorflow    | CVE-2021-41212 | Data processing | raggedcross                                    |
|   101  | Tensorflow    | CVE-2021-41211 | Data processing | QuantizeV2                                     |
|   102  | Tensorflow    | CVE-2021-41210 | Data processing | SparseCountSparseOutput                        |
|   103  | Tensorflow    | CVE-2021-41207 | Data processing | ParallelConcat                                 |
|   104  | Tensorflow    | CVE-2021-41205 | Data processing | QuantizeAndDequantizeV                         |
|   105  | Tensorflow    | CVE-2021-41202 | Data processing | range                                          |
|   106  | Tensorflow    | CVE-2021-41200 | Storing         | createfilewriter                               |
|   107  | Tensorflow    | CVE-2021-41199 | Data processing | resize                                         |
|   108  | Tensorflow    | CVE-2021-41198 | Data processing | tile                                           |
|   109  | Tensorflow    | CVE-2021-41196 | Data processing | MaxPooling3D                                   |
|   110  | Tensorflow    | CVE-2021-41195 | Data processing | AddDim                                         |
|   111  | Tensorflow    | CVE-2021-37688 | Data processing | invoke                                         |
|   112  | Tensorflow    | CVE-2021-37687 | Data processing | GatherNd                                       |
|   113  | Tensorflow    | CVE-2021-37679 | Data processing | mapfn                                          |
|   114  | Tensorflow    | CVE-2021-37678 | Data Loading    | modelfromyaml                                  |
|   115  | Tensorflow    | CVE-2021-37677 | Data processing | Dequantize                                     |
|   116  | Tensorflow    | CVE-2021-37676 | Data processing | SparseFillEmptyRows                            |
|   117  | Tensorflow    | CVE-2021-37675 | Data processing | Conv2D                                         |
|   118  | Tensorflow    | CVE-2021-37674 | Data processing | MaxPoolGrad                                    |
|   119  | Tensorflow    | CVE-2021-37673 | Data processing | MapStage                                       |
|   120  | Tensorflow    | CVE-2021-37672 | Data processing | SdcaOptimizerV2                                |
|   121  | Tensorflow    | CVE-2021-37671 | Data processing | MapPeek                                        |
|   122  | Tensorflow    | CVE-2021-37670 | Data processing | UpperBound                                     |
|   123  | Tensorflow    | CVE-2021-37669 | Data processing | NonMaxSuppressionV5                            |
|   124  | Tensorflow    | CVE-2021-37668 | Data processing | UnravelIndex                                   |
|   125  | Tensorflow    | CVE-2021-37667 | Data processing | UnicodeEncode                                  |
|   126  | Tensorflow    | CVE-2021-37666 | Data processing | RaggedTensorToVariant                          |
|   127  | Tensorflow    | CVE-2021-37665 | Data processing | RequantizationRangePerChannel                  |
|   128  | Tensorflow    | CVE-2021-37664 | Data processing | BoostedTreesSparseCalculateBestFeatureSplit    |
|   129  | Tensorflow    | CVE-2021-37663 | Data processing | QuantizeV2                                     |
|   130  | Tensorflow    | CVE-2021-37662 | Data processing | BoostedTreesCalculateBestGainsPerFeature       |
|   131  | Tensorflow    | CVE-2021-37661 | Data processing | Variable                                       |
|   132  | Tensorflow    | CVE-2021-37660 | Data processing | InplaceSub                                     |
|   133  | Tensorflow    | CVE-2021-37659 | Data processing | SqrtGrad                                       |
|   134  | Tensorflow    | CVE-2021-37658 | Data processing | MatrixSetDiagV3                                |
|   135  | Tensorflow    | CVE-2021-37657 | Data processing | MatrixDiagV3                                   |
|   136  | Tensorflow    | CVE-2021-37656 | Data processing | RaggedTensorToSparse                           |
|   137  | Tensorflow    | CVE-2021-37655 | Data processing | ResourceScatterUpdate                          |
|   138  | Tensorflow    | CVE-2021-37654 | Data processing | ResourceGather                                 |
|   139  | Tensorflow    | CVE-2021-37653 | Data processing | ResourceGather                                 |
|   140  | Tensorflow    | CVE-2021-37652 | Data processing | BoostedTreesCreateEnsemble                     |
|   141  | Tensorflow    | CVE-2021-37651 | Data processing | FractionalAvgPoolGrad                          |
|   142  | Tensorflow    | CVE-2021-37650 | Storing         | ExperimentalDatasetToTFRecord                  |
|   143  | Tensorflow    | CVE-2021-37649 | Data processing | UncompressElement                              |
|   144  | Tensorflow    | CVE-2021-37648 | Data processing | SaveV2                                         |
|   145  | Tensorflow    | CVE-2021-37647 | Data processing | SparseTensorSliceDataset                       |
|   146  | Tensorflow    | CVE-2021-37646 | Data processing | StringNGrams                                   |
|   147  | Tensorflow    | CVE-2021-37645 | Data processing | QuantizeAndDequantizeV4Grad                    |
|   148  | Tensorflow    | CVE-2021-37644 | Data processing | TensorListReserve                              |
|   149  | Tensorflow    | CVE-2021-37643 | Data processing | MatrixDiagPartV2                               |
|   150  | Tensorflow    | CVE-2021-37642 | Data processing | ResourceScatterDiv                             |
|   151  | Tensorflow    | CVE-2021-37641 | Data processing | RaggedGather                                   |
|   152  | Tensorflow    | CVE-2021-37640 | Data processing | SparseReshape                                  |
|   153  | Tensorflow    | CVE-2021-37639 | Data Loading    | Restore                                        |
|   154  | Tensorflow    | CVE-2021-37638 | Data processing | RaggedTensorToTensor                           |
|   155  | Tensorflow    | CVE-2021-37637 | Data processing | CompressElement                                |
|   156  | Tensorflow    | CVE-2021-37636 | Data processing | SparseDenseCwiseDiv                            |
|   157  | Tensorflow    | CVE-2021-37635 | Data processing | SparseTensor                                   |
|   158  | Tensorflow    | CVE-2021-29618 | Data processing | transpose                                      |
|   159  | Tensorflow    | CVE-2021-29617 | Data processing | substr                                         |
|   160  | Tensorflow    | CVE-2021-29614 | Data processing | decoderaw                                      |
|   161  | Tensorflow    | CVE-2021-29613 | Data processing | CTCLoss                                        |
|   162  | Tensorflow    | CVE-2021-29612 | Data processing | BandedTriangularSolve                          |
|   163  | Tensorflow    | CVE-2021-29611 | Data processing | SparseReshape                                  |
|   164  | Tensorflow    | CVE-2021-29610 | Data processing | QuantizeAndDequantizeV2                        |
|   165  | Tensorflow    | CVE-2021-29609 | Data processing | SparseAdd                                      |
|   166  | Tensorflow    | CVE-2021-29608 | Data processing | RaggedTensorToTensor                           |
|   167  | Tensorflow    | CVE-2021-29607 | Data processing | SparseSparseMinimum                            |
|   168  | Tensorflow    | CVE-2021-29584 | Data processing | SparseSplit                                    |
|   169  | Tensorflow    | CVE-2021-29583 | Data processing | FusedBatchNorm                                 |
|   170  | Tensorflow    | CVE-2021-29582 | Data processing | Dequantize                                     |
|   171  | Tensorflow    | CVE-2021-29581 | Data processing | CTCBeamSearchDecoder                           |
|   172  | Tensorflow    | CVE-2021-29580 | Data processing | FractionalMaxPoolGrad                          |
|   173  | Tensorflow    | CVE-2021-29579 | Data processing | MaxPoolGrad                                    |
|   174  | Tensorflow    | CVE-2021-29578 | Data processing | FractionalAvgPoolGrad                          |
|   175  | Tensorflow    | CVE-2021-29577 | Data processing | AvgPool3DGrad                                  |
|   176  | Tensorflow    | CVE-2021-29576 | Data processing | MaxPool3DGradGrad                              |
|   177  | Tensorflow    | CVE-2021-29575 | Data processing | ReverseSequence                                |
|   178  | Tensorflow    | CVE-2021-29574 | Data processing | MaxPool3DGradGrad                              |
|   179  | Tensorflow    | CVE-2021-29573 | Data processing | MaxPoolGradWithArgmax                          |
|   180  | Tensorflow    | CVE-2021-29572 | Data processing | SdcaOptimizer                                  |
|   181  | Tensorflow    | CVE-2021-29571 | Data processing | DrawBoundingBoxesV2                            |
|   182  | Tensorflow    | CVE-2021-29570 | Data processing | MaxPoolGradWithArgmax                          |
|   183  | Tensorflow    | CVE-2021-29569 | Data processing | RequantizationRange                            |
|   184  | Tensorflow    | CVE-2021-29568 | Data processing | ParameterizedTruncatedNormal                   |
|   185  | Tensorflow    | CVE-2021-29567 | Data processing | SparseDenseCwiseMul                            |
|   186  | Tensorflow    | CVE-2021-29566 | Data processing | Dilation2DBackpropInput                        |
|   187  | Tensorflow    | CVE-2021-29565 | Data processing | SparseFillEmptyRows                            |
|   188  | Tensorflow    | CVE-2021-29564 | Data processing | EditDistance                                   |
|   189  | Tensorflow    | CVE-2021-29563 | Data processing | RFFT                                           |
|   190  | Tensorflow    | CVE-2021-29562 | Data processing | IRFFT                                          |
|   191  | Tensorflow    | CVE-2021-29561 | Data Loading    | LoadAndRemapMatrix                             |
|   192  | Tensorflow    | CVE-2021-29560 | Data processing | RaggedTensorToTensor                           |
|   193  | Tensorflow    | CVE-2021-29559 | Data processing | UnicodeEncode                                  |
|   194  | Tensorflow    | CVE-2021-29558 | Data processing | SparseSplit                                    |
|   195  | Tensorflow    | CVE-2021-29557 | Data processing | SparseMatMul                                   |
|   196  | Tensorflow    | CVE-2021-29556 | Data processing | Reverse                                        |
|   197  | Tensorflow    | CVE-2021-29555 | Data processing | FusedBatchNorm                                 |
|   198  | Tensorflow    | CVE-2021-29554 | Data processing | DenseCountSparseOutput                         |
|   199  | Tensorflow    | CVE-2021-29553 | Data processing | QuantizeAndDequantizeV3                        |
|   200  | Tensorflow    | CVE-2021-29552 | Data processing | UnsortedSegmentJoin                            |
|   201  | Tensorflow    | CVE-2021-29551 | Data processing | MatrixTriangularSolve                          |
|   202  | Tensorflow    | CVE-2021-29550 | Data processing | FractionalAvgPool                              |
|   203  | Tensorflow    | CVE-2021-29549 | Data processing | QuantizedAdd                                   |
|   204  | Tensorflow    | CVE-2021-29548 | Data processing | QuantizedBatchNormWithGlobalNormalization      |
|   205  | Tensorflow    | CVE-2021-29547 | Data processing | QuantizedBatchNormWithGlobalNormalization      |
|   206  | Tensorflow    | CVE-2021-29546 | Data processing | QuantizedBiasAdd                               |
|   207  | Tensorflow    | CVE-2021-29545 | Data processing | SparseTensor                                   |
|   208  | Tensorflow    | CVE-2021-29544 | Data processing | QuantizeAndDequantizeV4Grad                    |
|   209  | Tensorflow    | CVE-2021-29543 | Data processing | CTCGreedyDecoder                               |
|   210  | Tensorflow    | CVE-2021-29542 | Data processing | StringNGrams                                   |
|   211  | Tensorflow    | CVE-2021-29541 | Data processing | StringNGrams                                   |
|   212  | Tensorflow    | CVE-2021-29540 | Data processing | Conv2DBackpropFilter                           |
|   213  | Tensorflow    | CVE-2021-29539 | Data processing | ImmutableConst                                 |
|   214  | Tensorflow    | CVE-2021-29538 | Data processing | Conv2DBackpropFilter                           |
|   215  | Tensorflow    | CVE-2021-29537 | Data processing | QuantizedResizeBilinear                        |
|   216  | Tensorflow    | CVE-2021-29536 | Data processing | QuantizedReshape                               |
|   217  | Tensorflow    | CVE-2021-29535 | Data processing | QuantizedMul                                   |
|   218  | Tensorflow    | CVE-2021-29534 | Data processing | SparseConcat                                   |
|   219  | Tensorflow    | CVE-2021-29533 | Data processing | DrawBoundingBoxes                              |
|   220  | Tensorflow    | CVE-2021-29532 | Data processing | RaggedCross                                    |
|   221  | Tensorflow    | CVE-2021-29531 | Data processing | EncodePng                                      |
|   222  | Tensorflow    | CVE-2021-29530 | Data processing | SparseTensor                                   |
|   223  | Tensorflow    | CVE-2021-29529 | Data processing | QuantizedResizeBilinear                        |
|   224  | Tensorflow    | CVE-2021-29528 | Data processing | QuantizedMul                                   |
|   225  | Tensorflow    | CVE-2021-29527 | Data processing | QuantizedConv2D                                |
|   226  | Tensorflow    | CVE-2021-29526 | Data processing | Conv2D                                         |
|   227  | Tensorflow    | CVE-2021-29525 | Data processing | Conv2DBackpropInput                            |
|   228  | Tensorflow    | CVE-2021-29524 | Data processing | Conv2DBackpropFilter                           |
|   229  | Tensorflow    | CVE-2021-29523 | Data processing | AddManySparseToTensorsMap                      |
|   230  | Tensorflow    | CVE-2021-29522 | Data processing | Conv3DBackpropInputV2                          |
|   231  | Tensorflow    | CVE-2021-29521 | Data processing | SparseCountSparseOutput                        |
|   232  | Tensorflow    | CVE-2021-29520 | Data processing | Conv3DBackpropInputV2                          |
|   233  | Tensorflow    | CVE-2021-29519 | Data processing | SparseCross                                    |
|   234  | Tensorflow    | CVE-2021-29518 | Data processing | GetSessionTensor                               |
|   235  | Tensorflow    | CVE-2021-29517 | Data processing | Conv3D                                         |
|   236  | Tensorflow    | CVE-2021-29516 | Data processing | Conv3D                                         |
|   237  | Tensorflow    | CVE-2021-29515 | Data processing | MatrixDiagV2                                   |
|   238  | Tensorflow    | CVE-2021-29513 | Data processing | truncatednormal                                |
|   239  | Tensorflow    | CVE-2021-29512 | Data processing | RaggedBincount                                 |
|   240  | Tensorflow    | CVE-2020-26269 | Data processing | GetMatchingPaths()                             |
|   241  | Tensorflow    | CVE-2020-26268 | Data processing | tf.raw_ops.ImmutableConst()                    |

|     **API Type**    |   **OpenCV**   |    **Numpy**   |   **Pillow**   | **TensorFlow** | **PyTorch** | **Caffe** |
|:-------------------:|:--------------:|:--------------:|:--------------:|:--------------:|:-----------:|:---------:|
| **Data Loading**    | CVE-2019-5064  | CVE-2014-1859  | CVE-2022-22816 | CVE-2021-37678 | N/A         | N/A       |
|                     | CVE-2019-5063  | CVE-2014-1858  | CVE-2022-22815 | CVE-2021-37639 |             |           |
|                     | CVE-2019-14493 |                | CVE-2021-28678 | CVE-2021-29561 |             |           |
|                     | CVE-2018-5269  |                | CVE-2021-28677 |                |             |           |
|                     | CVE-2018-5268  |                | CVE-2021-28675 |                |             |           |
|                     | CVE-2017-18009 |                | CVE-2021-27923 |                |             |           |
|                     | CVE-2017-17760 |                | CVE-2021-27922 |                |             |           |
|                     | CVE-2017-14136 |                | CVE-2021-27921 |                |             |           |
|                     | CVE-2017-12864 |                | CVE-2021-25292 |                |             |           |
|                     | CVE-2017-12863 |                | CVE-2020-5313  |                |             |           |
|                     | CVE-2017-12862 |                | CVE-2020-5312  |                |             |           |
|                     | CVE-2017-12606 |                | CVE-2020-5311  |                |             |           |
|                     | CVE-2017-12605 |                | CVE-2020-5310  |                |             |           |
|                     | CVE-2017-12604 |                | CVE-2020-35655 |                |             |           |
|                     | CVE-2017-12602 |                | CVE-2020-35654 |                |             |           |
|                     | CVE-2017-12600 |                | CVE-2020-35653 |                |             |           |
|                     | CVE-2017-12599 |                | CVE-2020-11538 |                |             |           |
|                     | CVE-2017-12598 |                | CVE-2020-10994 |                |             |           |
|                     | CVE-2017-12597 |                | CVE-2020-10379 |                |             |           |
|                     | CVE-2016-1517  |                | CVE-2020-10378 |                |             |           |
|                     |                |                | CVE-2020-10177 |                |             |           |
|                     |                |                | CVE-2019-19911 |                |             |           |
|                     |                |                | CVE-2019-16865 |                |             |           |
|                     |                |                | CVE-2016-9190  |                |             |           |
|                     |                |                | CVE-2016-9189  |                |             |           |
|                     |                |                | CVE-2016-3076  |                |             |           |
|                     |                |                | CVE-2016-2533  |                |             |           |
|                     |                |                | CVE-2016-0775  |                |             |           |
|                     |                |                | CVE-2016-0740  |                |             |           |
|                     |                |                | CVE-2014-9601  |                |             |           |
|                     |                |                | CVE-2014-3598  |                |             |           |
|                     |                |                | CVE-2014-3589  |                |             |           |
|                     |                |                | CVE-2014-3007  |                |             |           |
|                     |                |                | CVE-2014-1933  |                |             |           |
|                     |                |                | CVE-2014-1932  |                |             |           |
| **Data Processing** | CVE-2019-14492 | CVE-2017-12852 | CVE-2022-22817 | CVE-2022-23568 | N/A         | N/A       |
|                     | CVE-2019-14491 |                | CVE-2021-34552 | CVE-2022-23567 |             |           |
|                     |                |                | CVE-2021-28676 | CVE-2022-21740 |             |           |
|                     |                |                | CVE-2021-25293 | CVE-2022-21739 |             |           |
|                     |                |                | CVE-2021-25291 | CVE-2022-21738 |             |           |
|                     |                |                | CVE-2021-25290 | CVE-2022-21737 |             |           |
|                     |                |                | CVE-2021-25289 | CVE-2022-21736 |             |           |
|                     |                |                | CVE-2016-4009  | CVE-2022-21735 |             |           |
|                     |                |                |                | CVE-2022-21734 |             |           |
|                     |                |                |                | CVE-2022-21733 |             |           |
|                     |                |                |                | CVE-2022-21732 |             |           |
|                     |                |                |                | CVE-2022-21731 |             |           |
|                     |                |                |                | CVE-2022-21730 |             |           |
|                     |                |                |                | CVE-2022-21729 |             |           |
|                     |                |                |                | CVE-2022-21728 |             |           |
|                     |                |                |                | CVE-2022-21727 |             |           |
|                     |                |                |                | CVE-2022-21726 |             |           |
|                     |                |                |                | CVE-2022-21725 |             |           |
|                     |                |                |                | CVE-2021-41226 |             |           |
|                     |                |                |                | CVE-2021-41224 |             |           |
|                     |                |                |                | CVE-2021-41223 |             |           |
|                     |                |                |                | CVE-2021-41222 |             |           |
|                     |                |                |                | CVE-2021-41221 |             |           |
|                     |                |                |                | CVE-2021-41219 |             |           |
|                     |                |                |                | CVE-2021-41218 |             |           |
|                     |                |                |                | CVE-2021-41217 |             |           |
|                     |                |                |                | CVE-2021-41216 |             |           |
|                     |                |                |                | CVE-2021-41215 |             |           |
|                     |                |                |                | CVE-2021-41214 |             |           |
|                     |                |                |                | CVE-2021-41213 |             |           |
|                     |                |                |                | CVE-2021-41212 |             |           |
|                     |                |                |                | CVE-2021-41211 |             |           |
|                     |                |                |                | CVE-2021-41210 |             |           |
|                     |                |                |                | CVE-2021-41207 |             |           |
|                     |                |                |                | CVE-2021-41205 |             |           |
|                     |                |                |                | CVE-2021-41202 |             |           |
|                     |                |                |                | CVE-2021-41199 |             |           |
|                     |                |                |                | CVE-2021-41198 |             |           |
|                     |                |                |                | CVE-2021-41196 |             |           |
|                     |                |                |                | CVE-2021-41195 |             |           |
|                     |                |                |                | CVE-2021-37688 |             |           |
|                     |                |                |                | CVE-2021-37687 |             |           |
|                     |                |                |                | CVE-2021-37679 |             |           |
|                     |                |                |                | CVE-2021-37677 |             |           |
|                     |                |                |                | CVE-2021-37676 |             |           |
|                     |                |                |                | CVE-2021-37675 |             |           |
|                     |                |                |                | CVE-2021-37674 |             |           |
|                     |                |                |                | CVE-2021-37673 |             |           |
|                     |                |                |                | CVE-2021-37672 |             |           |
|                     |                |                |                | CVE-2021-37671 |             |           |
|                     |                |                |                | CVE-2021-37670 |             |           |
|                     |                |                |                | CVE-2021-37669 |             |           |
|                     |                |                |                | CVE-2021-37668 |             |           |
|                     |                |                |                | CVE-2021-37667 |             |           |
|                     |                |                |                | CVE-2021-37666 |             |           |
|                     |                |                |                | CVE-2021-37665 |             |           |
|                     |                |                |                | CVE-2021-37664 |             |           |
|                     |                |                |                | CVE-2021-37663 |             |           |
|                     |                |                |                | CVE-2021-37662 |             |           |
|                     |                |                |                | CVE-2021-37661 |             |           |
|                     |                |                |                | CVE-2021-37660 |             |           |
|                     |                |                |                | CVE-2021-37659 |             |           |
|                     |                |                |                | CVE-2021-37658 |             |           |
|                     |                |                |                | CVE-2021-37657 |             |           |
|                     |                |                |                | CVE-2021-37656 |             |           |
|                     |                |                |                | CVE-2021-37655 |             |           |
|                     |                |                |                | CVE-2021-37654 |             |           |
|                     |                |                |                | CVE-2021-37653 |             |           |
|                     |                |                |                | CVE-2021-37652 |             |           |
|                     |                |                |                | CVE-2021-37651 |             |           |
|                     |                |                |                | CVE-2021-37649 |             |           |
|                     |                |                |                | CVE-2021-37648 |             |           |
|                     |                |                |                | CVE-2021-37647 |             |           |
|                     |                |                |                | CVE-2021-37646 |             |           |
|                     |                |                |                | CVE-2021-37645 |             |           |
|                     |                |                |                | CVE-2021-37644 |             |           |
|                     |                |                |                | CVE-2021-37643 |             |           |
|                     |                |                |                | CVE-2021-37642 |             |           |
|                     |                |                |                | CVE-2021-37641 |             |           |
|                     |                |                |                | CVE-2021-37640 |             |           |
|                     |                |                |                | CVE-2021-37638 |             |           |
|                     |                |                |                | CVE-2021-37637 |             |           |
|                     |                |                |                | CVE-2021-37636 |             |           |
|                     |                |                |                | CVE-2021-37635 |             |           |
|                     |                |                |                | CVE-2021-29618 |             |           |
|                     |                |                |                | CVE-2021-29617 |             |           |
|                     |                |                |                | CVE-2021-29614 |             |           |
|                     |                |                |                | CVE-2021-29613 |             |           |
|                     |                |                |                | CVE-2021-29612 |             |           |
|                     |                |                |                | CVE-2021-29611 |             |           |
|                     |                |                |                | CVE-2021-29610 |             |           |
|                     |                |                |                | CVE-2021-29609 |             |           |
|                     |                |                |                | CVE-2021-29608 |             |           |
|                     |                |                |                | CVE-2021-29607 |             |           |
|                     |                |                |                | CVE-2021-29584 |             |           |
|                     |                |                |                | CVE-2021-29583 |             |           |
|                     |                |                |                | CVE-2021-29582 |             |           |
|                     |                |                |                | CVE-2021-29581 |             |           |
|                     |                |                |                | CVE-2021-29580 |             |           |
|                     |                |                |                | CVE-2021-29579 |             |           |
|                     |                |                |                | CVE-2021-29578 |             |           |
|                     |                |                |                | CVE-2021-29577 |             |           |
|                     |                |                |                | CVE-2021-29576 |             |           |
|                     |                |                |                | CVE-2021-29575 |             |           |
|                     |                |                |                | CVE-2021-29574 |             |           |
|                     |                |                |                | CVE-2021-29573 |             |           |
|                     |                |                |                | CVE-2021-29572 |             |           |
|                     |                |                |                | CVE-2021-29571 |             |           |
|                     |                |                |                | CVE-2021-29570 |             |           |
|                     |                |                |                | CVE-2021-29569 |             |           |
|                     |                |                |                | CVE-2021-29568 |             |           |
|                     |                |                |                | CVE-2021-29567 |             |           |
|                     |                |                |                | CVE-2021-29566 |             |           |
|                     |                |                |                | CVE-2021-29565 |             |           |
|                     |                |                |                | CVE-2021-29564 |             |           |
|                     |                |                |                | CVE-2021-29563 |             |           |
|                     |                |                |                | CVE-2021-29562 |             |           |
|                     |                |                |                | CVE-2021-29560 |             |           |
|                     |                |                |                | CVE-2021-29559 |             |           |
|                     |                |                |                | CVE-2021-29558 |             |           |
|                     |                |                |                | CVE-2021-29557 |             |           |
|                     |                |                |                | CVE-2021-29556 |             |           |
|                     |                |                |                | CVE-2021-29555 |             |           |
|                     |                |                |                | CVE-2021-29554 |             |           |
|                     |                |                |                | CVE-2021-29553 |             |           |
|                     |                |                |                | CVE-2021-29552 |             |           |
|                     |                |                |                | CVE-2021-29551 |             |           |
|                     |                |                |                | CVE-2021-29550 |             |           |
|                     |                |                |                | CVE-2021-29549 |             |           |
|                     |                |                |                | CVE-2021-29548 |             |           |
|                     |                |                |                | CVE-2021-29547 |             |           |
|                     |                |                |                | CVE-2021-29546 |             |           |
|                     |                |                |                | CVE-2021-29545 |             |           |
|                     |                |                |                | CVE-2021-29544 |             |           |
|                     |                |                |                | CVE-2021-29543 |             |           |
|                     |                |                |                | CVE-2021-29542 |             |           |
|                     |                |                |                | CVE-2021-29541 |             |           |
|                     |                |                |                | CVE-2021-29540 |             |           |
|                     |                |                |                | CVE-2021-29539 |             |           |
|                     |                |                |                | CVE-2021-29538 |             |           |
|                     |                |                |                | CVE-2021-29537 |             |           |
|                     |                |                |                | CVE-2021-29536 |             |           |
|                     |                |                |                | CVE-2021-29535 |             |           |
|                     |                |                |                | CVE-2021-29534 |             |           |
|                     |                |                |                | CVE-2021-29533 |             |           |
|                     |                |                |                | CVE-2021-29532 |             |           |
|                     |                |                |                | CVE-2021-29531 |             |           |
|                     |                |                |                | CVE-2021-29530 |             |           |
|                     |                |                |                | CVE-2021-29529 |             |           |
|                     |                |                |                | CVE-2021-29528 |             |           |
|                     |                |                |                | CVE-2021-29527 |             |           |
|                     |                |                |                | CVE-2021-29526 |             |           |
|                     |                |                |                | CVE-2021-29525 |             |           |
|                     |                |                |                | CVE-2021-29524 |             |           |
|                     |                |                |                | CVE-2021-29523 |             |           |
|                     |                |                |                | CVE-2021-29522 |             |           |
|                     |                |                |                | CVE-2021-29521 |             |           |
|                     |                |                |                | CVE-2021-29520 |             |           |
|                     |                |                |                | CVE-2021-29519 |             |           |
|                     |                |                |                | CVE-2021-29518 |             |           |
|                     |                |                |                | CVE-2021-29517 |             |           |
|                     |                |                |                | CVE-2021-29516 |             |           |
|                     |                |                |                | CVE-2021-29515 |             |           |
|                     |                |                |                | CVE-2021-29513 |             |           |
|                     |                |                |                | CVE-2021-29512 |             |           |
|                     |                |                |                | CVE-2020-26269 |             |           |
|                     |                |                |                | CVE-2020-26268 |             |           |
| **Storing**         | N/A            | N/A            | N/A            | CVE-2021-41200 | N/A         | N/A       |
|                     |                |                |                | CVE-2021-37650 |             |           |
| **Visualizing**     | N/A            | N/A            | CVE-2022-24303 | N/A            | N/A         | N/A       |
# Analyzed Applications

We searched popular applications under topic OpenCV, PyTorch, Caffe and TensorFlow. The popularity is measured by the number of stars.

We manually inspect the source code of these projects and find those popular deep learning framework based applications do not break the assumptions on the pipline data flow pattern.

## List of Applications and Security-sensitive Data

We identify four types of security-sensitive data (S<sub>1</sub> ~ S<sub>4</sub>).

| Symbol        | Sensitive Information                                             |
| ------------- | ----------------------------------------------------------------- |
| S<sub>1</sub> | Detected values of detected faces/objects/emotions from the input |
| S<sub>2</sub> | Outputs annotated with the results and sensitive information      |
| S<sub>3</sub> | Sensitive metadata that the program loads                         |
| S<sub>4</sub> | ML models and their configurations                                |

In below table, the third ~ fifth column show the sensitive data types each program includes, which we define as above.

| Framework  | Name                             | Phase 1 | Phase 2                      | Phase 3                      | Phase 4 | Source Code                                                             |
| ---------- | -------------------------------- | ------- | ---------------------------- | ---------------------------- | ------- | ----------------------------------------------------------------------- |
| OpenCV     | Face_Recognition                 | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>, S<sub>3</sub> | None    | [Link](https://github.com/ageitgey/face_recognition)                    |
| OpenCV     | faceai                           | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/vipstone/faceai)                              |
| OpenCV     | BossSensor                       | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/Hironsan/BossSensor)                          |
| OpenCV     | tiler                            | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/nuno-faria/tiler)                             |
| OpenCV     | sistine                          | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/bijection/sistine)                            |
| OpenCV     | trace.moe                        | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>, S<sub>3</sub> | None    | [Link](https://github.com/soruly/trace.moe)                             |
| OpenCV     | mathAI                           | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/Roujack/mathAI)                               |
| OpenCV     | Is-Now-Illegal                   | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>, S<sub>3</sub> | None    | [Link](https://github.com/ivanseidel/Is-Now-Illegal)                    |
| OpenCV     | video-to-ascii                   | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/joelibaceta/video-to-ascii)                   |
| OpenCV     | DeepNude_NoWatermark_withModel   | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/zhengyima/DeepNude_NoWatermark_withModel)     |
| OpenCV     | idcardgenerator                  | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/airob0t/idcardgenerator)                      |
| OpenCV     | eyeLike                          | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/trishume/eyeLike)                             |
| OpenCV     | Anime-InPainting                 | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/youyuge34/Anime-InPainting)                   |
| OpenCV     | lbpcascade_animeface             | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/nagadomi/lbpcascade_animeface)                |
| OpenCV     | captcha-break                    | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>, S<sub>3</sub> | None    | [Link](https://github.com/nladuo/captcha-break)                         |
| OpenCV     | vehicle_detection                | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/tatsuyah/vehicle-detection)                   |
| PyTorch    | Real-Time-Voice-Cloning          | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/CorentinJ/Real-Time-Voice-Cloning)            |
| PyTorch    | pytorch-CycleGAN-and-pix2pix     | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix)         |
| PyTorch    | mmdetection                      | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/open-mmlab/mmdetection)                       |
| PyTorch    | fairseq                          | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/pytorch/fairseq)                              |
| PyTorch    | EasyOCR                          | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>, S<sub>3</sub> | None    | [Link](https://github.com/JaidedAI/EasyOCR)                             |
| PyTorch    | yolov5                           | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/ultralytics/yolov5)                           |
| PyTorch    | Bringing-Old-Photos-Back-to-Life | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/microsoft/Bringing-Old-Photos-Back-to-Life)   |
| PyTorch    | yolov3                           | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/ultralytics/yolov3)                           |
| PyTorch    | chineseocr_lite                  | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/ouyanghuiyu/chineseocr_lite)                  |
| PyTorch    | pix2pixHD                        | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/NVIDIA/pix2pixHD)                             |
| PyTorch    | stargan                          | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/yunjey/stargan)                               |
| PyTorch    | SiamMask                         | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/foolwood/SiamMask)                            |
| PyTorch    | Pytorch-UNet                     | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/milesial/Pytorch-UNet)                        |
| PyTorch    | EfficientNet-PyTorch             | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/lukemelas/EfficientNet-PyTorch)               |
| PyTorch    | Semantic-Segmentation            | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/CSAILVision/semantic-segmentation-pytorch)    |
| TensorFlow | Real-Time-Voice-Cloning          | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/CorentinJ/Real-Time-Voice-Cloning)            |
| TensorFlow | DeepSpeech                       | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/mozilla/DeepSpeech)                           |
| TensorFlow | facenet                          | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/davidsandberg/facenet)                        |
| TensorFlow | DeepCreamPy                      | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/deeppomf/DeepCreamPy)                         |
| TensorFlow | Learning-to-See-in-the-Dark      | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/cchen156/Learning-to-See-in-the-Dark)         |
| TensorFlow | tf-pose-estimation               | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/ildoonet/tf-pose-estimation)                  |
| TensorFlow | CapsNet-Tensorflow               | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/naturomics/CapsNet-Tensorflow)                |
| TensorFlow | text-classification-cnn-rnn      | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/gaussic/text-classification-cnn-rnn)          |
| TensorFlow | tensorflow-yolov3                | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/YunYang1994/tensorflow-yolov3)                |
| TensorFlow | tensorflow_poems                 | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/jinfagang/tensorflow_poems)                   |
| TensorFlow | Automatic_Speech_Recognition     | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/zzw922cn/Automatic_Speech_Recognition)        |
| TensorFlow | AnimeGAN                         | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/TachibanaYoshino/AnimeGAN)                    |
| TensorFlow | srgan                            | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/tensorlayer/srgan)                            |
| TensorFlow | DCGAN-TensorFlow                 | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/carpedm20/DCGAN-tensorflow)                   |
| TensorFlow | Style-Transfer                   | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/lengstrom/fast-style-transfer)                |
| Caffe      | openpose                         | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/CMU-Perceptual-Computing-Lab/openpose)        |
| Caffe      | MobileNet-SSD                    | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/chuanqi305/MobileNet-SSD)                     |
| Caffe      | EmoRecon                         | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/sushant3095/RealtimeFacialEmotionRecognition) |
| Caffe      | MTCNN                            | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/CongWeilin/mtcnn-caffe)                       |
| Caffe      | FaceMaskDetection                | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/AIZOOTech/FaceMaskDetection)                  |
| Caffe      | face_verification                | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>, S<sub>3</sub> | None    | [Link](https://github.com/AlfredXiangWu/face_verification_experiment)   |
| Caffe      | Face-Mask-Detection              | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/chandrikadeb7/Face-Mask-Detection)            |
| Caffe      | person_search                    | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>, S<sub>3</sub> | None    | [Link](https://github.com/ShuangLI59/person_search)                     |
| Caffe      | multi-object-tracker             | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/adipandas/multi-object-tracker)               |
| Caffe      | caffe-yolov3                     | None    | S<sub>1</sub>, S<sub>4</sub> | S<sub>2</sub>                | None    | [Link](https://github.com/ChenYingpeng/caffe-yolov3)                    |
