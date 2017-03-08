<!--
If your issue is a usage or a general question, please submit it here instead:
- Mailing List: https://groups.google.com/forum/#!forum/gensim
For more information, see Recipes&FAQ: https://github.com/RaRe-Technologies/gensim/wiki/Recipes-&-FAQ
-->

<!-- Instructions For Filing a Bug: https://github.com/RaRe-Technologies/gensim/blob/develop/CONTRIBUTING.md -->

#### Description
TODO: change commented example
<!-- Example: Joblib Error thrown when calling fit on LatentDirichletAllocation with evaluate_every > 0-->

#### Steps/Code/Corpus to Reproduce
<!--
Example:
```
from sklearn.feature_extraction.text import CountVectorizer
from sklearn.decomposition import LatentDirichletAllocation

docs = ["Help I have a bug" for i in range(1000)]

vectorizer = CountVectorizer(input=docs, analyzer='word')
lda_features = vectorizer.fit_transform(docs)

lda_model = LatentDirichletAllocation(
    n_topics=10,
    learning_method='online',
    evaluate_every=10,
    n_jobs=4,
)
model = lda_model.fit(lda_features)
```
If the code is too long, feel free to put it in a public gist and link
it in the issue: https://gist.github.com
-->

#### Expected Results
<!-- Example: No error is thrown. Please paste or describe the expected results.-->

#### Actual Results
<!-- Please paste or specifically describe the actual output or traceback. -->

#### Versions
<!--
Please run the following snippet and paste the output below.
import platform; print(platform.platform())
import sys; print("Python", sys.version)
import numpy; print("NumPy", numpy.__version__)
import scipy; print("SciPy", scipy.__version__)
import gensim; print("gensim", gensim.__version__)
from gensim.models import word2vec;print("FAST_VERSION", word2vec.FAST_VERSION)
-->


<!-- Thanks for contributing! -->

