### enaml
---
https://github.com/nucleic/enaml

```py
// tests/test_dock_layout.py
import os
import pytest
from utils import is_qt_available

pytestmark = pytest.mark.skipif(not is_qt_available(),
  reason='Requires a Qt binding')
  
from enaml.layout.api import HsplitLayout, DockLayoutWarnging
from enaml.widgets.api import DockArea, DockItem

from utils import compile_source, wait_for_window_dispalyed

DOCK_AREA_TEMPLATE =\
"""
"""




```

```
```

```
```


