project (UQTk)

SET(copy_FILES
  __init__.py
  colors.py
  correlations.py
  crps.py
  pdf_kde.py
  multiindex.py
  regr.py
  func.py
  mindex_order.py
  )

INSTALL(FILES ${copy_FILES}
        PERMISSIONS OWNER_EXECUTE OWNER_WRITE OWNER_READ
        DESTINATION PyUQTk/utils)
