# pdfmerge

Example
<?php
require('PdfMerge.php');

$merge = new PdfMerge();
$merge->add('doc1.pdf');
$merge->add('doc2.pdf');
$merge->output();
?>
