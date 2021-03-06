# Go packages

github.com/kniren/gota/dataframe    
github.com/go-hep/csvutil    
github.com/go-hep/csvutil/csvdriver   
github.com/lib/pq    
github.com/patrickmn/go-cache    
github.com/boltdb/bolt    
github.com/gonum/matrix/mat64    
github.com/gonum/stat    
github.com/montanaflynn/stats    
github.com/gonum/plot     
github.com/gonum/plot/plotter    
github.com/gonum/plot/vg     
github.com/gonum/stat/distuv    
github.com/gonum/mathext     
bitbucket.org/zombiezen/gopdf/pdf      
github.com/biogo/graphics/bezier     
github.com/gonum/floats     
github.com/sajari/regression     
github.com/sjwhitworth/golearn/base     
github.com/sjwhitworth/golearn/evaluation    
github.com/sjwhitworth/golearn/knn     
github.com/sjwhitworth/golearn/trees    
github.com/Sirupsen/logrus 

# Other dependencies

- A free "tiny turtle" Postgres instance on [ElephantSQL](https://www.elephantsql.com/)
- `psql` 9.2+
- A [local installation of Pachyderm](http://pachyderm.readthedocs.io/en/stable/getting_started/local_installation.html).
- A specific version of `google.golang.com/grpc`:
    
    ```
    go get google.golang.org/grpc
    cd $GOPATH/src/google.golang.org/grpc
    git checkout 9d682f9293b408c42d17c587d0e2a31237ac3f10
    ```
