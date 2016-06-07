# SQLstuff

Making Postgres Views - #CREATE VIEW view_name as select * FROM table;

now this view can be use as  select * FROM view_name;


CALCULATE if table exists or not -

#select exists(select * from information_schema.tables where table_name=table_name);

In python for above query

#cursor.fetchone()[0] return true or false
                                
