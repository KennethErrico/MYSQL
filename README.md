Kenneth Errico
# MYSQL
Advanced Database Management
Taken with Prof. Russell Gouveia at NECC


FINAL PROJECT STAGE 5

This is a relational database using MYSQL on a CentOS Server (similar to RedHat). 
The instructions served as a guide to be followed loosely and creativity was encouraged. 
The attached DUMP file can be uploaded to a Linux server or virtual machine for further inspection.



           DIVISION                                                               MAJOR            PERSON
              |                                                                      \            /  |  \
              |                                                                       \          /   |   \
              |                                                                        \        /    |    \
           DEPARTMENT                      DIAGRAM                                      \      /     |     \ 
               \                              OF                                        STUDENT    STAFF   FACULTY
                \                         RELATIONAL                                      |                    |
                 \                         DATABASE                                       |                    |
                  \                                                                 STU_SEC_BRIDGE       FAC_SEC_BRIDGE
                   \                                                                      \                   /
                    \                                                                      \                 /
                     \                                                                      \               /
                      \                                                                      \             /
                       \                                                                      \           /
                        \                                                                      \         /
                      COURSE---------------------------------------------------------------------SECTION
                    /   |   \                                                                       |
                   /    |    \                                                                      |
                  /     |     \                                                                     |
                 /      |      \                                                              ROOM_SEC_BRIDGE
                /       |       \                                                                   |
      CRS_CAT_BRIDGE    |    CRS_TYPE_BRIDGE                                                        |
         /              |          \                                                                |
        /               |           \                                                              ROOM
    CATEGORY            |           TYPE(CLASS)                                                   /    \
                        |                                                                        /      \
                   DEG_CRS_BRIDGE                                                               /        \
                        |                                                                      /          \
                        |                                                                 ROOM_TYPE     BUILDING
                      DEGREE                                                                                |
                                                                                                            |
                                                                                                         CAMPUS
                                                                                                         
                                                                                                         
